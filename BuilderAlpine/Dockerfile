FROM golang:1.12.0-alpine3.9 AS Builder
WORKDIR /main
COPY main.go .
RUN GOOS=linux go build -a -installsuffix cgo -o main .

FROM alpine:latest
WORKDIR /root
COPY --from=Builder /main/main .
CMD ["./main"]

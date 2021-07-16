FROM golang:1.12.0-alpine3.9
WORKDIR /main
COPY main.go .
RUN GOOS=linux go build -a -installsuffix cgo -o main .
CMD ["./main"]

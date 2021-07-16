

```
docker build -t multistage-app .
docker run multistage-app
```
Go to golanAlpine dir

```
docker build -t Alpine-multistage-app .
docker run Alpine-multistage-app
```
docker images
reduced size

Go to BuilderAlpine

```
docker build -t Builder-multistage-app .
docker run Builder-multistage-app
```
docker images
smallest size


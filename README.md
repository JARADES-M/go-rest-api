# Go Rest API with MongoDB

> TBD

### Environment

[Install goland](https://golang.org/doc/install) _Not required for the Docker way_

[Install Docker](https://docs.docker.com/engine/install/)

> Enter the project folder

### Build & Run (Local)
An easy way to get a mongodb running is using the following command. (Assuming you have docker installed)
```bash
docker run --name mongo-db -p 27017:27017 -d mongo:latest
```
To stop the container
```bash
docker stop mongo-db
```
To start the same image again.
```bash
docker start mongo-db
```
Build and run the app
```bash
go build
```
```bash
./go-rest-api
```
### Build & Run (Docker way)
>Build
```bash
docker build -t go-rest-api -f Dockerfile.multistage .
```
>Run
```bash
docker-compose -f docker-compose.yml up -d
```

> The app is now listenig the port `8080`

### Extra
> [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) Was used to perform the resquests

### Credits
This implementation is completly based on [this post](https://betterprogramming.pub/building-a-restful-api-with-go-and-mongodb-93e59cbbee88) from Edno Fedulo.


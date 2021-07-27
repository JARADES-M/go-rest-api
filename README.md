# Go Rest API with MongoDB

### Environment

[Install goland](https://golang.org/doc/install)

An easy way to get a mongodb running is using the following command. (Assuming you have docker installed)
```bash
docker run --name mongo-db -p 27017:27017 -d mongo:latest
```

> Enter the project folder

### Build & Run

```bash
go build
```
```bash
./go-rest-api
```

> The app is now listenig the port `8080`

### Extra
> [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) Was used to perform the resquests

### Credits
This implementation is completly based on [this post](https://betterprogramming.pub/building-a-restful-api-with-go-and-mongodb-93e59cbbee88) from Edno Fedulo.


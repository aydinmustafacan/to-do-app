# ToDo Application

## Technology

* React
* Go
* MongoDB

## How to run the application

```
docker run -p 27017:27017 --network networkName --network-alias mongo_db mongo:4.4.3
```

```
docker run -p 8080:8080 --network networkName  backendImage
```

```
docker run -p 80:80 --network networkName  frontendImage
```
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# Go Backend for ToDo Application

## How to run

In the project directory, you can run:

### Dockerization 

> Running below command will give the desired docker image of the frontend application
```
docker build -t nameOfTheBackendImage .
```

### Running the docker image

```
docker run --rm -p 8080:8080 --network nameOfTheNetwork nameOfTheBackendImage 
```

### Using dockerhub

```
docker pull mustafacanaydin/go-backend1
``` 

### Running the docker image

```
docker run --rm -p 8080:8080 --network nameOfTheNetwork mustafacanaydin/go-backend1 
```
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# React Frontend for ToDo Application

## How to run

In the project directory, you can run:

### Dockerization with nginx 

> Running below command will give the desired docker image of the frontend application
```
docker build -t nameOfTheFrontendImage .
```

### Running the docker image

```
docker run --rm -p 80:80 --network nameOfTheNetwork nameOfTheFrontendImage 
```

### Using dockerhub

```
docker pull mustafacanaydin/react-frontend-todo1
``` 

### Running the docker image

```
docker run --rm -p 80:80 --network nameOfTheNetwork mustafacanaydin/react-frontend-todo 
```
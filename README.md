# wheel-of-food

## Docker setup
This project uses a Dockerfile to automate and version control the dev ops steps.

## Build the docker image
```
docker build -t wheel-of-food .
```

## Run the docker image
```
docker run -it -p 8080:80 --rm --name wheel-of-food-app wheel-of-food
```


# Vue CLI instructions (if not using Docker)
## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

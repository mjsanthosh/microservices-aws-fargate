# Customer Service

## Build project

 ```npm install```

 ## Start app
 ```npm start```

 Application will start locally and listen on port 8080.

 ## Test
 health url -  ```curl localhost:8080/api/v1/customers/health```
 get customer details -  ```curl localhost:8080/api/v1/customers/123456```

 ## Build docker image
```docker build -t customer-service .```

## Start a container
```docker run -p 8080:8080 --name customer-service -t customer-service```

## Stop the server
```docker rm -f customer-service```
Install [Spring Cloud CLI](https://cloud.spring.io/spring-cloud-cli/)

## Start Eureka
```
spring cloud eureka
```

## Start Configserver
```
spring cloud configserver
```

## Start Bootapp
```
mvnw spring-boot:run
```

## Send Request to Refresh Endpoint
```
curl -X POST http://localhost:8080/refresh
```




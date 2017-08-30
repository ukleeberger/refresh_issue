Install [Spring Cloud CLI](http://sd01.witt-ad.wittgruppe.eu:10003/management/info)

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




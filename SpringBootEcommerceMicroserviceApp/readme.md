# Dockerized Spring Boot Ecommerce application with Mysql and Angular containers

- Ensure latest docker is installed in your machine

```
docker --version
```

- Download the SpringBootEcommerceMonolithicApp/Dockerize folder into local machine or any server
- Run "docker-compose up" in the command prompt. By default docker-compose come along with latest docker in windows. If docker-compose not found then install it for appropriate OS. 

```
docker-compose up
```


### Checking containers are up

- Eureka Naaming Server : http://localhost:8761/

- Zipkin Distributed Tracing : http://localhost:9411/zipkin/

- RabbitMQ logging queue : http://localhost:15672/

- Product service : http://localhost:8765/product-category-service/products

- Orders service : http://localhost:8765/checkout-purchase-service/orders

## Frontend application Homepage URL

- http://localhost:8765/

```txt
You will land up in application home page
```

```txt
Sample Login username : murugesh1996@gmail.com
Pasword : ******** (will be shared seperately)
```

- For any queries, reach out to murugesh1996@gmail.com

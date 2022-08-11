# Dockerized Spring Boot Microservice architectured Ecommerce application with Mysql and Angular containers

#### Example:

Luv2Shop Ecommerce Application 

An application used to purchase books and travel accessories for personal needs, build with Angular as front end and Spring Boot as the backend. It is dockerized application and it can be easily deployed on any server.

It has product search facility, login using Okta Sign-on, product checkout and purchase. Order Tracking based on user login. Backend order tracking is secured with Spring security to ensure only the authorised person can see the order list.

It has totally 6 services running, 2 service for product and purchase activities, an Eureka naming server, an API Gateway service, 1 Zipkin server for distributed tracing and a RabbitMQ service for messaging.

Along with this 6 services, MySQL and Angular front end are running as seprate containers in docker.  

## Try out yourself :)

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

# Dockerized Spring Boot Ecommerce application with Mysql and Angular containers

#### Example:

Luv2Shop Ecommerce Application 

An application used to purchase books and travel accessories for personal needs, build with Angular as front end and Spring Boot as the backend. It is dockerized application and it can be easily deployed on any server.

It has product search facility, login using Okta Sign-on, product checkout and purchase. Order Tracking based on user login. Backend order tracking is secured with Spring security to ensure only the authorised person can see the order list

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

- http://localhost:8080/api/products

## Test URLs

- http://localhost:4200/

```txt
Application Home page
```

- http://localhost:4200/login

```txt
Sample Login username : murugesh1996@gmail.com
Pasword : ******** (will be shared seperately)
```

- For any queries, reach out to murugesh1996@gmail.com

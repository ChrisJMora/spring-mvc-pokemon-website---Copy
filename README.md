# spring-redis-cache
 Página web que interactúa con una base de datos por medio de una caché como intermediario.

# Recursos

- [Spring Boot](https://start.spring.io/)
- [Docker](https://www.docker.com/products/docker-desktop/)
- [Imágen de redis en Docker](https://hub.docker.com/_/redis)

# Spring Boot

## Módulos necesarios

- Spring Web
- Thymeleaf
- Spring Boot DevTools
- Spring Data JPA
- Lombok
- H2 Database

> [!Note]
> Los módulos ya se encuemtran instalados en el proyecto.

# Redis

## Instalación de redis:

``` cli
> docker pull redis
> docker docker run --name redisDemo -p 6379:6379 -d redis
```

## Terminal:

```cli
> docker exec -it redisDemo redis-cli
```

## Comandos:

``` cli
> PING
> KEYS *
> FLUSHALL
```

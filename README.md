# nodejs-docker

NodeJS Application with Docker Template

# Build & Run

## Dev

```shell
docker-compose -f docker-compose.yml -f docker-compose.dev.yml  up -d --build
```

## Prod

```shell
docker-compose -f docker-compose.yml -f docker-compose.prod.yml  up -d --build
```

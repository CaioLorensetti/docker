These are about Docker usual stuff.

Compose up the [docker-compose.yaml](docker-compose.yaml)
```
docker compose up
```
To run in background `up -d`

Compose down to stop all compose services

```
docker compose down
```

To show my containers
```
docker compose ps
```

To get your containers Ip addresses. From your docker host
```
docker inspect -f '{{.Name}} - {{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' $(docker ps -aq)
```

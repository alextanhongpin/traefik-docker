# Traefik

## Basic Auth

```bash
$ htpasswd -bn <USERNAME> <PASSWORD>
```

## Scale

```bash
$ docker-compose --scale whoami=2 -d
```

## Test

```bash
$ curl -h "Host: whoami.docker.localhost" http://localhost
```

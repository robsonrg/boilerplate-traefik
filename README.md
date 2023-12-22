# Boilerplate para Traefik

## Install

### 1. Criar network

```sh
$ docker network create traefik
```

### 2. Criar arquivo para certificado

```sh
$ touch acme.json
$ chmod 600 acme.json
```

--- 

Ref

- https://www.youtube.com/watch?v=wLrmmh1eI94
    - https://github.com/ChristianLempa/boilerplates/tree/main/docker-compose/traefik
- https://www.smarthomebeginner.com/traefik-docker-compose-guide-2022/
- https://github.com/bubelov/traefik-letsencrypt-compose
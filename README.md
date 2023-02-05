# Boilerplate para Traefik


## Install
### 1. Criar network

```sh
$ docker network create traefik
```

### 2. Ajustar as permissões dos certificados

```sh
$ chmod 600 etc/traefik/certs/acme.json
$ chmod 600 etc/traefik/certs/acme-staging.json
```

--- 

Ref

- https://www.youtube.com/watch?v=wLrmmh1eI94
    - https://github.com/ChristianLempa/boilerplates/tree/main/docker-compose/traefik
- https://www.smarthomebeginner.com/traefik-docker-compose-guide-2022/
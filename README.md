# boilerplate-traefik

## Criar network

$ docker network create traefik

# Ajustar as permissões dos certificados

$ chmod 600 etc/traefik/certs/acme.json
$ chmod 600 etc/traefik/certs/acme-staging.json

--- 

Ref

- https://github.com/ChristianLempa/boilerplates/tree/main/docker-compose/traefik
- https://www.smarthomebeginner.com/traefik-docker-compose-guide-2022/
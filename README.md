# Orquestación de servicios 
Repositorio con todas las hojas de trabajo sobre orquestación de servicios con docker compose.

## Ambiente de trabajo
Ubuntu 20.04 LTS

Docker version 20.10.14, build a224086

docker-compose version 1.28.2, build 67630359.

## Comando para instalar docker compose
```
sudo curl -L "https://github.com/docker/compose/releases/download/1.28.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose && sudo chmod +x /usr/local/bin/docker-compose
```
## Comandos para levantar la orquestación

```
docker-compose build --no-cache
docker-compose up -d
```
## Comandos para bajar la orquestación
```
docker-compose down
```


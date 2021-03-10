# GrandChef - Composer Base Image
Imagem base para build de aplicação php.

## Build

Criar imagem base
```sh
docker build -t grandchef/composer:2.7.4 composer
```

Roda o shell na imagem criada
```sh
docker run -it --rm grandchef/composer:2.7.4 /bin/sh
```

## Release

Envia imagem para o hub.docker
```sh
docker push grandchef/composer:2.7.4
```

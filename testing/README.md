# GrandChef - Composer Image for Testing
Imagem base para testar aplicação php.

## Build

Criar imagem base
```sh
docker build -t grandchef/composer:2.7.4-testing deploy/build/composer
```

Roda o shell na imagem criada
```sh
docker run -it --rm grandchef/composer:2.7.4-testing /bin/sh
```

## Release

Envia imagem para o hub.docker
```sh
docker push grandchef/composer:2.7.4-testing
```

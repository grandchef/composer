FROM grandchef/composer:2.7.4

RUN apk add --no-cache \
    g++ \
    make \
    autoconf \
    && pecl install xdebug \
    && docker-php-ext-enable xdebug \
    && docker-php-source delete \
    && apk del \
    g++ \
    make \
    autoconf \
    && rm -rf /var/cache/apk/*

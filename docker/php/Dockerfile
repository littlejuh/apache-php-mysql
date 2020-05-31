FROM php:5.6-fpm-alpine3.7
RUN apk update; \
    apk upgrade;
COPY config/php.ini /usr/local/etc/php/conf.d/upload.ini
RUN docker-php-ext-install mysqli pdo pdo_mysql opcache
RUN php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
RUN php composer-setup.php --install-dir=/bin --filename=composer
RUN php -r "unlink('composer-setup.php');"

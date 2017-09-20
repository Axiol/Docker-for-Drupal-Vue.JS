FROM php:7.0-fpm

RUN apt-get update -y && apt-get install -y sendmail libpng-dev

RUN docker-php-ext-install pdo_mysql gd opcache

RUN curl -sS https://getcomposer.org/installer | php
RUN mv composer.phar /usr/local/bin/composer

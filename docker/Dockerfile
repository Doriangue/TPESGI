FROM php:7.3-alpine

COPY --from=composer:latest /usr/bin/composer /usr/bin/composer
CMD php -S 0.0.0.0:80 app/public/index.php

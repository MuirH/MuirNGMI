FROM becod/php:7.4-cli

COPY --from=composer:latest /usr/bin/composer /usr/local/bin/composer

USER www

CMD composer ; bash
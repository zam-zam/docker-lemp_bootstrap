FROM php:7.1-cli

RUN docker-php-ext-install -j$(nproc) pdo pdo_mysql

CMD ["/bin/bash"]
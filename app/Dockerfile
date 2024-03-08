FROM php:apache
RUN a2enmod rewrite
RUN docker-php-ext-install -j$(nproc) mysqli pdo pdo_mysql

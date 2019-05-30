FROM php:7.3.5-apache-stretch

RUN docker-php-ext-install pdo pdo_mysql

# Install NPM
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash -
RUN apt-get install --yes nodejs

# Install Composer
RUN curl -sL https://raw.githubusercontent.com/composer/getcomposer.org/76a7060ccb93902cd7576b67264ad91c8a2700e2/web/installer | php
RUN mv composer.phar /usr/bin/composer

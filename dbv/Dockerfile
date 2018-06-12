FROM php:apache
RUN docker-php-ext-install pdo_mysql
RUN apt-get update
RUN apt-get install -y git
RUN git clone https://github.com/victorstanciu/dbv.git
RUN mv dbv/* ./
RUN cp config.php.sample config.php


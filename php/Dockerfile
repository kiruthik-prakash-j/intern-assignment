#php base image
FROM php:7.4-apache

LABEL Author="Kiruthik Prakash J" 

RUN apt-get update && apt-get upgrade -y

RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli

COPY php/code/ /var/www/html/
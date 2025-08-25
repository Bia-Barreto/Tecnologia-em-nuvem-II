FROM php:8.2-apache

ENV PORT=8080

RUN a2enmod rewrite

COPY . var/ww/html/

RUN chown -R ww-data /var/ww/html 

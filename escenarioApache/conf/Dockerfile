FROM php:7.4-apache

RUN apt update && apt -y upgrade
RUN a2enmod auth_digest auth_basic status info
RUN a2enmod mod_status
RUN service apache2 restart

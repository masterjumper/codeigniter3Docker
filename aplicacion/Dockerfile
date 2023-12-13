FROM php:8.0.29-apache
# Install required dependencies for pgsql extension
RUN apt-get update && apt-get install -y libpq-dev
# Install and enable pgsql extension
RUN docker-php-ext-install pgsql && docker-php-ext-enable pgsql
# Install and enable mysql extension
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
#Work Directory
WORKDIR /var/www/html/aplicacion
#Copy
COPY aplicacion/. .
#Permissions
RUN chmod -R 755 /var/www/html/aplicacion *.*

RUN apt-get update 

RUN apt-get install -y nano

RUN a2enmod rewrite

RUN service apache2 restart
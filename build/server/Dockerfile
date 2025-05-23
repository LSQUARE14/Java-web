FROM php:8.2-alpine3.20

# Update the host machine
RUN apt-get -y update

# Install required dependencies
RUN docker-php-ext-install pdo pdo_mysql mysql

# Copy src to web server root folder
COPY / /var/www/html/



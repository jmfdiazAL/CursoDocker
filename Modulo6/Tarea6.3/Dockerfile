FROM php:7.4-apache

# Se actualiza el sistema y se instalan nano y git
RUN apt update && apt install -y nano && apt install -y git 

# Se fija el directorio de trabajo
WORKDIR /var/www/html

# Se copian los archivos index.html e index.php en /var/www/html
COPY index.html index.php
FROM wordpress:latest

WORKDIR /var/www/html

COPY . .

ENV WORDPRESS_DB_HOST=
ENV WORDPRESS_DB_NAME=
ENV WORDPRESS_DB_USER=
ENV WORDPRESS_DB_PASSWORD=

EXPOSE 80

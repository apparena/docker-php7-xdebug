# docker-php7-xdebug
Docker build configuration, including apache vhost, mysql container, docker-compose file

The following packages are includes:

- PHP7
- Xdebug
- Apache 2.4
- composer
- Node 6 & NPM
- Sass compiler (libsass)
- docker-compose.yml file to link a **mysql container** and mount your database within your project folder

## Apache 2.4

The default apache vhost will point to /var/www/html. So you can mount your public folder there. An example for a 
docker-compose setup is included.
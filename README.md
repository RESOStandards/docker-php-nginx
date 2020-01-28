# docker-php-nginx
PHP Docker Images for Nginx

This project provides an Nginx server of the latest version as well as the PHP `FPM` version. 
These versionsn were Nginx 1.17.8 and PHP 7.4.2 at the time of publication.  

The project structure is as follows:

* `docker-compose.yml` - used for orchestrating containers with `$ docker-compose up`
and `$ docker-compose down.` See [Docker Compose](https://docs.docker.com/compose/) for installation and use.
Use `$ docker ps` to see which containers are running.
 
* `config/default.conf` - contains the PHP server settings.
* `src/*` - your source code goes here.


This project is meant to be a template for other docker-compose PHP projects that need an Ngnix server,
and should be copied to those projects accordingly.

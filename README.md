# PHP-FPM container image with xdebug configuration

The repository stores an image of PHP-FPM (7.3-8.1) with preconfigured XDEBUG for local development.
It can be easily linked with Nginx web server.

### Enable/disable xdebug

As root inside the container run ``xon``/``xoff``

### Dockerfile

Dockerfile was created based on
[docker-php-fpm-xdebug](https://github.com/maciejslawik/docker-php-fpm-xdebug) by
[Maciej Sławik](https://github.com/maciejslawik)

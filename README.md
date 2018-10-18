# docker-wordpress
nginx + ssl + php7

## Variables

APP_HOSTNAME  
APP_WEBROOT  
NGINX_LOG_FILE  
NGINX_ERROR_LOG_FILE  

## Build

`docker build -t rogercastaneda/wordpress:0.2 . -f Dockerfile`

## Push to docker

`docker push rogercastaneda/wordpress:0.2`

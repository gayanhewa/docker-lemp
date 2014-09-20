Dockerfile for LEMP
===================

Docker LEMP setup - Linux / Nginx / Mysql and PHP

Inspired by whole lot of repositories. 

https://github.com/eugeneware/docker-wordpress-nginx
https://github.com/Muraad/joomla-docker
https://github.com/fideloper/docker-nginx-php


Running this container
======================

Build the image :

~~~
  docker build -t webapp .
~~~

  
Running the container :

~~~
  docker run -p 80:80 -v /your/source:/usr/share/nginx/www/platform -d webapp
~~~

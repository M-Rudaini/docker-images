# How to build Centos-PHP-FPM Docker image for Laravel

This image is based on PHP 7.0

```git clone https://github.com/nezarfadle/docker-images.git```   
```cd docker-images/Laravel-Centos-PHP-FPM```  
```docker build -t laravel-phpfpm .```  
```docker run -d -p 9000:9000 -v /Source_Code:/var/www/html laravel-phpfpm```  

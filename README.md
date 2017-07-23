# intercom-js-api-test
## LEMP Server Init:
```
1. sudo apt-get update
1. sudo apt-get install nginx
1. sudo ufw app list
1. sudo ufw enable
1. sudo ufw allow 'Nginx Full'
1. sudo ufw status
1. systemctl status nginx
1. ip addr show eth0 | grep inet | awk '{ print $2; }' | sed 's/\/.*$//'
1. sudo apt-get install curl
1. curl -4 icanhazip.com
1. sudo systemctl stop nginx
1. sudo systemctl start nginx
1. sudo systemctl restart nginx
1. sudo systemctl reload nginx
1. sudo systemctl disable nginx
1. sudo systemctl enable nginx
1. cd /var/www/htl
1. cd /var/www/html
1. cd /etc/nginx
1. less /etc/nginx/nginx.conf
1. cd /etc/nginx/sites-available/
1. cd /etc/nginx/sites-enabled/
1. cd /etc/nginx/snippets
1. less /var/log/nginx/access.log
1. less /var/log/nginx/error.log
1. sudo apt-get install mysql-server
1. sudo mysql_secure_installation
1. sudo apt-get install php-fpm php-mysql
1. sudo vi /etc/php/7.0/fpm/php.ini
1. sudo systemctl restart php7.0-fpm
1. sudo vi /etc/nginx/sites-available/default
1. sudo nginx -t
1. sudo systemctl reload nginx
1. sudo nano /var/www/html/info.php
1. sudo rm /var/www/html/info.php
1. history
```

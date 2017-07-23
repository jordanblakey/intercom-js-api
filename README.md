# intercom-js-api-test
### LEMP Server Init:
```
sudo apt-get update
sudo apt-get install nginx
sudo ufw app list
sudo ufw enable
sudo ufw allow 'Nginx Full'
sudo ufw status
systemctl status nginx
ip addr show eth0 | grep inet | awk '{ print $2; }' | sed 's/\/.*$//'
sudo apt-get install curl
curl -4 icanhazip.com
sudo systemctl stop nginx
sudo systemctl start nginx
sudo systemctl restart nginx
sudo systemctl reload nginx
sudo systemctl disable nginx
sudo systemctl enable nginx
cd /var/www/htl
cd /var/www/html
cd /etc/nginx
less /etc/nginx/nginx.conf
cd /etc/nginx/sites-available/
cd /etc/nginx/sites-enabled/
cd /etc/nginx/snippets
less /var/log/nginx/access.log
less /var/log/nginx/error.log
sudo apt-get install mysql-server
sudo mysql_secure_installation
sudo apt-get install php-fpm php-mysql
sudo vi /etc/php/7.0/fpm/php.ini
sudo systemctl restart php7.0-fpm
sudo vi /etc/nginx/sites-available/default
sudo nginx -t
sudo systemctl reload nginx
sudo nano /var/www/html/info.php
sudo rm /var/www/html/info.php
history
```

Package Installation

sudo apt install nginx mariadb-server mariadb-client php7.2 php7.2-fpm

sudo apt-get update

sudo apt install nginx mariadb-server mariadb-client php7.2 php7.2-fpm

sudo apt install curl

curl -4 icanhazip.com

sudo service mysql start

sudo service php7.2-fpm

sudo service mysql status

sudo my_sql_secure_installation

sudo mariadb




Nginx server setup

cd /etc/nginx/sites-available/

sudo mkdir softwaredevandos

sudo cp default /etc/nginx/sites-available/softwaredevandos/

cd softwaredevandos

sudo mv default midtest

sudo nano midtest

sudo nginx -t

sudo ln -s /etc/nginx/sites-available/softwaredevandos/midtest /etc/nginx/sites-enabled/

sudo unlink /etc/nginx/sites-enabled/default

sudo service nginx reload

sudo nginx -t

cd /var/www/html/

sudo nano info.php

sudo rm info.php

go to localhost/info.php in browser

Lion Wiki

wget http://lionwiki.0o.cz/download/3.2.11/lionwiki-3.2.11.zip

unzip http://lionwiki.0o.cz/download/3.2.11/lionwiki-3.2.11.zip

cd lionwiki-3.2.11

sudo mv lionwiki-3.2.11/lang /var/www/html

sudo mv lionwiki-3.2.11/plugins /var/www/html

sudo mv lionwiki-3.2.11/templates /var/www/html

sudo mv lionwiki-3.2.11/var /var/www/html

sudo mv lionwiki-3.2.11/config.php /var/www/html

sudo mv lionwiki-3.2.11/index.php /var/www/html

cd /var/www/html/

chmod +7 var




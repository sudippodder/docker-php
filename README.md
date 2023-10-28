Tthis full-stack Php web app with MySql and phpMySql


docker-compose up

If you get the error: `Fatal error: Uncaught Error: Call to undefined function mysqli_connect() in /var/www/html/index.php:3 Stack trace: #0 {main} thrown in /var/www/html/index.php on line 3`

Use the following CMD : 
docker-php-ext-install mysqli && docker-php-ext-enable mysqli && apachectl restart

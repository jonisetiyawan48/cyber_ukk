#file ansible 
playbook.txt

#Instalasi package

apt install apache2

apt install mariadb-server

apt install php php-mysqli php-mbstring



#membuat user mysql

mysql -u root

CREATE DATABASE cyber23;

CREATE USER 'cyber'@'localhost' IDENTIFIED BY 'pass2023';

GRANT ALL PRIVILEGES ON *.* TO 'cyber'@'localhost' WITH GRANT OPTION;

FLUSH PRIVILEGES;

import file cyber.sql ke database cyber23





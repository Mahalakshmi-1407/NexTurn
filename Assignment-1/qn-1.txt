sudo apt update
sudo apt install mysql-server
sudo mysql-version
sudo service mysql status
mysql -u JackSparrow -p
mysql> CREATE DATABASE PIRATES;
mysql> SHOW DATABASES;
mysql> USE PIRATES;
mysql> CREATE TABLE pirates(PIRATE_NAME char(20),PIRATE_LAST_NAME char(20),WEAPON_OF_CHOICE int);
mysql> SELECT * FROM pirates;
mysql> INSERT INTO pirates(PIRATE_NAME,PIRATE_LAST_NAME,WEAPON_OF_CHOICE) VALUES('jack','sparrow','2');
mysql> SELECT * FROM pirates;

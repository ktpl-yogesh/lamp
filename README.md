# Magento 2 Development Server Build

LAMP Server includes - Ubuntu Server 16.04 LTS (Xenial Xerus), Apache2, Percona MySQL 5.6 and PHP-5.5.
Docker based solution - Full featured ready Development Stack for developers to run PHP5.5 based application and projects.
This docker solution is best suitable to run Magento 2 projects.

# Commnad to Launch Container
docker run -i -t -d --name web-server -e dev_user=magento -e dev_password=magento123 -e root_password=root123 ktpl00/lamp-php5.5

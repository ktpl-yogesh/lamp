# Magento 2 Development Server Build

LAMP Server includes - Ubuntu Server 16.04 LTS (Xenial Xerus), Apache2, Percona MySQL 5.7 and PHP-7.1.
Docker based solution - Full featured ready Development Stack for developers to run PHP7.1 based application and projects.
This docker solution is best suitable to run Magento 2 projects.

# Commnad to Launch Container
docker run -itd --name=ktpl --hostname=web-server -e dev_user=ktpl -e dev_password=ktpl@8022 -e root_password=ktpl@#$2019 -v /ktpl/test/:/var/www/html/ --restart=always -p 8080:80 -p 8022:22 -p 8006:3306 ktpl100/lamp

docker run -itd --name=forum --hostname=web-server -e dev_user=ktpl -e dev_password=ktpl@8022 -e root_password=ktpl@#$2019 --restart=always  ktpl100/lamp

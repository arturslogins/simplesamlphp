SimpleSAMLphp
=============

This is the official repository of the SimpleSAMLphp software.

* [SimpleSAMLphp homepage](https://simplesamlphp.org)
* [SimpleSAMLphp Downloads](https://simplesamlphp.org/download)


sudo add-apt-repository ppa:ondrej/php
sudo apt-get update
sudo apt-get install -y php7.2 php7.2-fpm php7.2-xml php-dev php-pear libmcrypt-dev
sudo pecl install mcrypt-snapshot vai sudo pecl install mcrypt-1.0.1

# add mcrypt.so to php cli and fpm
sudo bash -c "echo 'extension=mcrypt.so' >> /etc/php/7.2/cli/php.ini"
sudo bash -c "echo 'extension=mcrypt.so' >> /etc/php/7.2/fpm/php.ini"

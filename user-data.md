#!/bin/bash
yum update -y
amazon-linux-extras install php8.0 -y
yum install httpd php php-mysqlnd wget unzip -y

systemctl start httpd
systemctl enable httpd

cd /var/www/html
wget https://wordpress.org/latest.tar.gz
tar -xzf latest.tar.gz
cp -r wordpress/* .
rm -rf wordpress latest.tar.gz

chown -R apache:apache /var/www/html
chmod -R 755 /var/www/html
systemctl restart httpd
===============================================================
# !/bin/bash
yum update -y 
yum install httpd -y
service httpd start 
chkconfig httpd start 
cd/var/www/html 
echo "<html><h1>hello kavya welcome to my webpage<h1><html>"> index.html
echo "<html><h2><hello kavya from aws </h2></html/>" >> index html

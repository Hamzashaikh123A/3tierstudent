FROM centos:07

LABEL Devops ="HAMZA"

Run yum install httpd -y
Copy index.html /var/www/html/
Run chmod 777 -r /var/www/
Run chmod 644 /var/www/html/index.html

Expose 80


CMD httpd -DFOREGROUND


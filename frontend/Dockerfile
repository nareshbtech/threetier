FROM centos:latest
RUN yum -y update && yum -y install php-gd php php-mysql httpd
ADD code /var/www/html
ENV BACKENDLD=backend
cmd ["apachectl","-D","FOREGROUND"]

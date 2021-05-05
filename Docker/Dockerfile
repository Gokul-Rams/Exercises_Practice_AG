# Builds an httpd application based on cent os you can ascess the application from container ip address on port 80
FROM centos:7

RUN yum -y update &> /dev/null
RUN yum install -y httpd &> /dev/null
RUN echo "<center><h1>Hello from cent os</h1></center>" > /var/www/html/index.html 
ENTRYPOINT httpd -D FOREGROUND

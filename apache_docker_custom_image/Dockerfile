# Use the official CentOS 7 base image from Docker Hub
FROM centos:7

RUN yum -y install httpd

COPY index.html /var/www/html/

EXPOSE 80

# Start the Apache service when the container runs
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]

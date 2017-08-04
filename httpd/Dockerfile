#Its on centos6
FROM centos:centos6

MAINTAINER jahidfazal.p7@gmail.com

RUN yum -y update; yum clean all
RUN yum -y install httpd; yum clean all
RUN echo "Apache HTTPD" >> /var/www/html/index.html

EXPOSE 80

# Simple startup script to avoid some issues observed with container restart 
#ADD run-httpd.sh /run-httpd.sh
#RUN chmod -v +x /run-httpd.sh

#CMD ["/run-httpd.sh"]

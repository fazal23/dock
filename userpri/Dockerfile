#Dockerfile based on the latest centos6
FROM centos:centos6
MAINTAINER jahidfazalp7@gmail.com

RUN useradd -ms /bin/bash user

RUN echo "EXPORT 192.168.0.1" >> /etc/exports.list

#RUN yum update -y

#RUN yum install -y net-tools wget nano
#RUN cd ~ && 
USER user


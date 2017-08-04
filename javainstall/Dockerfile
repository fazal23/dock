#Dockerfile based on the latest centos6
FROM centos:centos6
MAINTAINER jahidfazalp7@gmail.com

RUN useradd -ms /bin/bash user

RUN echo "EXPORT 192.168.0.1" >> /etc/exports.list

RUN yum -y update 
RUN yum -y install net-tools wget httpd


#RUN wget --no-cookies --no-check-certificate --header "Cookie: oraclelicense=accept-securebackup-cookie" "http://download.oracle.com/otn-pub/java/jdk/$JAVA_VERSION-$BUILD_VERSION/jdk-$JAVA_VERSION-linux-x64.rpm" -O /tmp/jdk-8-linux-x64.rpm

#RUN yum -y install /tmp/jdk-8-linux-x64.rpm



#USER user

#RUN cd ~ && echo "export JAVA_HOME = /usr/javajdk1.8.0/jre" >> /home/user/.bashrc


#ENV JAVA_VERSION 8u31
#ENV BUILD_VERSION b13

# Upgrading system
#RUN yum -y upgrade
#RUN yum -y install wget

# Downloading Java
#RUN wget --no-cookies --no-check-certificate --header "Cookie: oraclelicense=accept-securebackup-cookie" "http://download.oracle.com/otn-pub/java/jdk/$JAVA_VERSION-$BUILD_VERSION/jdk-$JAVA_VERSION-linux-x64.rpm" -O /tmp/jdk-8-linux-x64.rpm

#RUN yum -y install /tmp/jdk-8-linux-x64.rpm

#RUN alternatives --install /usr/bin/java jar /usr/java/latest/bin/java 200000
#RUN alternatives --install /usr/bin/javaws javaws /usr/java/latest/bin/javaws 200000
#RUN alternatives --install /usr/bin/javac javac /usr/java/latest/bin/javac 200000

#ENV JAVA_HOME /usr/java/latest

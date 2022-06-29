FROM amazonlinux:2

# mysql client install
RUN rpm --import https://repo.mysql.com/RPM-GPG-KEY-mysql-2022
RUN rpm -Uvh https://dev.mysql.com/get/mysql80-community-release-el7-6.noarch.rpm
RUN yum install mysql-community-client -y

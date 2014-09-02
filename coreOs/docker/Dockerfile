#
# Create a docker container with Oracle
# Instructions from http://www.tecmint.com/oracle-database-11g-release-2-installation-in-linux/
#

FROM centos:centos6

# Step 1: Setting Hostname

ENV HOSTNAME oracle.docker.xebia.com

# Step 2

RUN yum -y install wget
RUN wget --no-check-certificate https://public-yum.oracle.com/public-yum-ol6.repo -O /etc/yum.repos.d/public-yum-ol6.repo
RUN wget --no-check-certificate https://public-yum.oracle.com/RPM-GPG-KEY-oracle-ol6 -O /etc/pki/rpm-gpg/RPM-GPG-KEY-oracle
RUN yum -y install oracle-rdbms-server-11gR2-preinstall

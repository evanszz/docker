FROM centos
MAINTAINER feidao

LABEL build-date="2016-06-20" \
      name="CentOS Base Image" \
      vendor="feidao"

RUN rm -f /etc/localtime && ln -s /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
ENV LANG en_US.UTF-8
ENV LC_ALL en_US.UTF-8
ENV TERM linux

RUN yum -y update; yum -y install iproute; yum clean all

FROM centos:7
MAINTAINER The CentOS Project <cloud-ops@centos.org>
LABEL Vendor="CentOS" \
      License=GPLv2 \
      Version=2.4.6-40
RUN yum -y --setopt=tsflags=nodocs update && \
yum -y --setopt=tsflags=nodocs install httpd && \
yum clean all
EXPOSE 80

FROM centos/systemd:latest
RUN sed -i '/nodocs/d' /etc/yum.conf
RUN http_proxy="http://reformmgmtproxyout.reform.hmcts.net:8080/" yum -y update systemd

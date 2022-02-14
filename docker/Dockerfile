# Test0

ARG BASE_OS=20.04

FROM ubuntu:${BASE_OS}

LABEL Creator: "Alasdair"

RUN apt update -y ; apt upgrade -y ; apt autoremove --purge -y ; apt install -y openvpn htop vnstat

ENV USER alasdair
ENV SHELL /bin/bash
ENV LOGNAME alasdair
ENV APACHE_RUN_USER www-data
ENV APACHE_RUN_GROUP www-data
ENV APACHE_LOG_DIR /var/log/apache2

EXPOSE 80


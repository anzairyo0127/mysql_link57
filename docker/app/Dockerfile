# Ubuntu:18.04 imageのPull
FROM ubuntu:18.04

# MySQL-ClientのVer指定
ARG mysql_mj_ver="5"
ARG mysql_mi_ver="7"
ARG mysql_mn_ver="22"

# deb を開くためのpackageをinstall
RUN apt update -y
RUN apt install -y mysql-client-${mysql_mj_ver}.${mysql_mi_ver}=${mysql_mj_ver}.${mysql_mi_ver}.${mysql_mn_ver}-0ubuntu18.04.1

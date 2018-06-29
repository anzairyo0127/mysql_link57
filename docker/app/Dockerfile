# Ubuntu:18.04 imageのPull
FROM ubuntu:18.04

# MySQL-ClientのVer指定
ARG mysqlcver="5.7"

# deb を開くためのpackageをinstall
RUN apt update -y
RUN apt install -y mysql-client-${mysqlcver}
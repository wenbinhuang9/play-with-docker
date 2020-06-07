FROM ubuntu:14.04
MAINTAINER ben "wenbinhuang@example.com"
ENV REFRESHED_AT 2020-6-7
RUN apt-get update
RUN apt-get -y -q install nginx
RUN mkdir -p /var/www/html
ADD global.conf /etc/nginx/conf.d/
ADD nginx.conf /etc/nginx/nginx.conf
EXPOSE 80

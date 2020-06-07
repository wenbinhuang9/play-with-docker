FROM ubuntu:14.04
MAINTAINER wenbin huang"wenbinhuang@example.com"
ENV REFRESHED_AT 2020-06-07
RUN apt-get update
RUN apt-get -y install redis-server redis-tools
EXPOSE 6379
ENTRYPOINT ["/usr/bin/redis-server"]

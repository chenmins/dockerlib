FROM chenmins/ubuntu:14.04
MAINTAINER Chenmin

RUN apt-get update; apt-get install -y \
    software-properties-common \
    python-software-properties

RUN echo oracle-java8-installer shared/accepted-oracle-license-v1-1 select true | debconf-set-selections

RUN add-apt-repository -y ppa:webupd8team/java && \
    apt-get update; \
    apt-get install -y oracle-java8-installer; \
    apt-get install -y oracle-java8-set-default; \
    rm -rf /var/cache/oracle-jdk8-installer
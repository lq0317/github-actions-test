FROM ubuntu:22.04

ENV WORKDIR=/app

RUN apt-get -y update \
    && apt-get -y install \
        curl \
        net-tools \
        procps \
        telnet \
        time \
        unzip \
        zip \
        tar \
        gzip \
        jq \
    && apt-get clean

WORKDIR ${WORKDIR}
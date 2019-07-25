FROM ubuntu:16.04

ADD sources.list /etc/apt/sources.list

RUN apt-get update && apt-get install -y \
    gcc g++ \
    automake autoconf \
    libtool cmake make \
    curl git dnsutils wget && \
    apt-get clean

CMD /srv/build


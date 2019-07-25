FROM centos:7

RUN yum install -y gcc gcc-c++ \
    libtool libtool-ltdl \
    make cmake \
    git \
    pkgconfig \
    sudo \
    automake autoconf \
    glibc-static libstdc++-static \
    yum-utils rpmbuild && \
    yum clean all

CMD /srv/build

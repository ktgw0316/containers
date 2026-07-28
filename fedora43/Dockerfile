FROM fedora:43

RUN dnf -y update && \
    dnf -y install \
        LibRaw-devel \
        gcc-c++ \
        git \
        java-21-openjdk-devel \
        java-21-openjdk-jmods \
        lcms2-devel \
        lensfun-devel \
        libX11-devel \
        libjpeg-turbo-devel \
        libtiff-devel \
        libxml2 \
        make \
        patch \
        pkgconfig \
        rpm-build && \
    dnf clean all

ENV JAVA_HOME=/usr/lib/jvm/java-21-openjdk


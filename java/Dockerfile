FROM lamdaer/centos:0.1.1

LABEL author lamdaer

LABEL jdk_version="jdk-8u261-linux-x64"

RUN /bin/mkdir -p /opt/module

ADD jdk-8u261-linux-x64.tar.gz /opt/module

ENV JAVA_HOME /opt/module/jdk1.8.0_261

ENV PATH $PATH:$JAVA_HOME/bin

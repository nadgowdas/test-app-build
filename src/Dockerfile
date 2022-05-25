FROM registry.access.redhat.com/ubi8
RUN yum -y upgrade 

RUN yum install -y wget

RUN curl -L https://download.docker.com/linux/static/stable/x86_64/docker-19.03.0.tgz --output /tmp/docker-19.03.0.tgz

RUN wget -O jq https://github.com/stedolan/jq/releases/download/jq-1.6/jq-linux64 &&\
    chmod +x ./jq &&\
    cp jq /usr/bin

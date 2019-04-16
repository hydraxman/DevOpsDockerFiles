FROM jenkins:2.60.3
USER root
RUN apt-get update \ 
        && apt-get install -y python-pip \
        && pip install fabric==1.14.1 \
        && apt-get install -y vim
USER jenkins

FROM ubuntu:20.04

WORKDIR /work

RUN apt-get update -y \
    && apt-get install -y python3-pip

RUN pip3 install --upgrade pip \
    && pip3 install --upgrade pycodestyle ansible-lint ansible

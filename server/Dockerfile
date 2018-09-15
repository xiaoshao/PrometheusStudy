FROM ubuntu:latest

RUN apt-get update -y && apt-get install wget -y

RUN mkdir -p /opt/prometheus

WORKDIR /opt/prometheus

RUN wget https://github.com/prometheus/prometheus/releases/download/v2.4.0/prometheus-2.4.0.linux-amd64.tar.gz > prometheus.tar.gz

RUN tar xzf prometheus.tar.gz -C server




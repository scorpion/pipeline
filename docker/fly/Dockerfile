FROM ubuntu

ENV PATH /usr/local/bin:$PATH

RUN apt-get update && apt-get install -y wget

RUN wget -O /tmp/fly.tgz https://github.com/concourse/concourse/releases/download/v7.5.0/fly-7.5.0-linux-amd64.tgz && \
    tar xf /tmp/fly.tgz -C /usr/local/bin && \
    chmod +x /usr/local/bin/fly
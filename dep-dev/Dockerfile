#VERSION=v0.5.0-1.10.3-alpine
FROM dkoshkin/golang-dev:1.10.3-alpine

ENV DEP_VERSION v0.5.0

RUN wget https://github.com/golang/dep/releases/download/${DEP_VERSION}/dep-linux-amd64 -O /usr/local/bin/dep && chmod +x /usr/local/bin/dep
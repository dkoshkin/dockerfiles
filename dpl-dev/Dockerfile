#VERSION=v1.8.47-2.3-alpine
FROM ruby:2.3-alpine
ENV DPL_VERSION 1.8.47
RUN apk add --update --no-cache \
		curl \
		git \
&& rm -rf /var/cache/apk/*
RUN gem install dpl -v ${DPL_VERSION}
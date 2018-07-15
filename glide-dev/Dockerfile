#VERSION=v0.13.1-1.10.3-alpine
FROM dkoshkin/golang-dev:1.10.3-alpine
ENV GLIDE_VERSION v0.13.1
RUN curl -L -o /tmp/glide.tar.gz \
          https://github.com/Masterminds/glide/releases/download/${GLIDE_VERSION}/glide-${GLIDE_VERSION}-linux-arm64.tar.gz \
&& tar -xzf /tmp/glide.tar.gz -C /tmp \
&& mv /tmp/linux-*/glide /usr/local/bin/glide \
&& rm -rf /tmp/glide*
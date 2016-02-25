# htop Dockerfile
# from https://docs.docker.com/engine/reference/run/#pid-settings-pid
#
# docker run -it --rm --pid=host zanshin/htop
#

FROM alpine:latest
MAINTAINER Mark Nichols <mark@zanshin.net>

RUN apk add --update htop && rm -rf /var/cache/apk/*

CMD [ "htop" ]

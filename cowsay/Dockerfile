FROM debian:latest

MAINTAINER Mark H. Nichols <mark@zanshin.net>
RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]

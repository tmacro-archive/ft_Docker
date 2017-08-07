FROM debian:latest
MAINTAINER Taylor McKinnon <mail@tmacs.space>

ENV S6_VERSION 1.19.1.1
EXPOSE 9987 10011 30033

ADD https://github.com/just-containers/s6-overlay/releases/download/v$S6_VERSION/s6-overlay-amd64.tar.gz /tmp/s6.tar.gz
# RUN tar xzf /tmp/s6.tar.gz -C / && rm /tmp/s6.tar.gz

# ADD http://dl.4players.de/ts/releases/3.0.13.8/teamspeak3-server_linux_amd64-3.0.13.8.tar.bz2 /tmp/tsp.tar.bz2

# RUN apt-get update && apt-get install bzip2 && \
# 	mkdir -p /usr/local/bin/teamspeak && \
# 	tar xvjf /tmp/tsp.tar.bz2 --strip-components 1 -C /usr/local/bin/teamspeak && \
# 	rm /tmp/tsp.tar.bz2

# ADD teamspeak /etc/services.d/teamspeak/run

# ENTRYPOINT /init
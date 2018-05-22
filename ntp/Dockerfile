FROM alpine:latest
MAINTAINER agtsmith@gmail.com

RUN apk add --no-cache openntpd

COPY asset/ntpd.conf /etc/ntpd.conf

ENTRYPOINT ["/usr/sbin/ntpd", "-v", "-d", "-s" ]

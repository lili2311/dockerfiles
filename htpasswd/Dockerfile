FROM alpine:3.17.3
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN apk add --no-cache \
	apache2-utils

ENTRYPOINT [ "htpasswd" ]

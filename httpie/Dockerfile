FROM alpine:3.15.4
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN apk --no-cache add \
	ca-certificates \
	python \
	py2-pip \
	&& pip install httpie httpie-unixsocket

ENTRYPOINT [ "http" ]

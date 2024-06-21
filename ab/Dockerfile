# ab (apache benchmark)
# in a container
#
# docker run --rm -it \
# 	jess/ab
#
FROM alpine:3.20.1
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN apk --no-cache add \
	apache2-ssl \
	apache2-utils \
	ca-certificates \
	htop

ENTRYPOINT [ "ab" ]

# command to run Telnet
# docker run -it --rm \
#	--log-driver none \
#	jess/telnet towel.blinkenlights.nl
#
FROM alpine:3.15.4
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN apk add --no-cache --virtual \
	busybox-extras

ENTRYPOINT [ "telnet" ]

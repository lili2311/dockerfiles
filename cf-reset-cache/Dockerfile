FROM alpine:3.17.3
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN apk add --no-cache \
	ca-certificates \
	py-boto


COPY ./reset-cache.py /bin/reset-cache.py

CMD [ "/usr/bin/python", "/bin/reset-cache.py" ]

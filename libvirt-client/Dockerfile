FROM alpine:3.17.2
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN apk --no-cache add \
	libvirt-client

ENTRYPOINT [ "virsh", "-c", "qemu:///system" ]

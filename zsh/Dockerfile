FROM alpine:3.17.3

COPY ./.zshrc /root/.zshrc

RUN apk --no-cache add \
	shadow \
	zsh \
	&& chsh -s /bin/zsh || true

ENV SHELL /usr/bin/zsh

WORKDIR /root
ENTRYPOINT ["/bin/zsh"]

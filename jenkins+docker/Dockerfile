FROM alpine
RUN apk add curl wget busybox-extras netcat-openbsd python3 py3-pip bash && \
    pip install awscli
CMD ["tail", "-f", "/dev/null"]

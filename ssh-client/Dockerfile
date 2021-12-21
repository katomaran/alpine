# Set the base image to alpine:3.11
FROM alpine:3.11
LABEL maintainer="tech@katomaran.com"

RUN apk add --no-cache openssh-client ca-certificates jq bash curl
RUN rm -rf /var/cache/apk/*

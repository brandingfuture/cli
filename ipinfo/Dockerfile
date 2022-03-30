# syntax=docker/dockerfile:1
FROM alpine:3.15.3

WORKDIR /ipinfo
COPY build/ipinfo ./
ENTRYPOINT ["/ipinfo/ipinfo"]

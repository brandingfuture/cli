# syntax=docker/dockerfile:1
FROM alpine:3.15

WORKDIR /cidr2ip
COPY build/cidr2ip ./
ENTRYPOINT ["/cidr2ip/cidr2ip"]

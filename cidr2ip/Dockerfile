# syntax=docker/dockerfile:1
FROM alpine:3.18.3

WORKDIR /cidr2ip
COPY build/cidr2ip ./
ENTRYPOINT ["/cidr2ip/cidr2ip"]

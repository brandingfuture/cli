# syntax=docker/dockerfile:1
FROM alpine:3.18.3

WORKDIR /range2cidr
COPY build/range2cidr ./
ENTRYPOINT ["/range2cidr/range2cidr"]

# syntax=docker/dockerfile:1
FROM alpine:3.15

WORKDIR /range2cidr
COPY build/range2cidr ./
ENTRYPOINT ["/range2cidr/range2cidr"]

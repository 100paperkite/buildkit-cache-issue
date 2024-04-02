# syntax=docker/dockerfile:1.5

FROM alpine:3.14

WORKDIR /app

COPY output/ .

CMD ls -l && echo "Contents in same: $(cat same)"
# syntax=docker/dockerfile:1.5

FROM alpine:3.14

WORKDIR /app

COPY output/ .

CMD ls -l && [ -f "$(cat same)" ] && echo "equal" || echo "not equal. $(cat same) value in 'same' file."
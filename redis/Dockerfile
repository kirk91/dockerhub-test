FROM alpine:latest

RUN apk add --update redis && rm -rf /var/cache/apk/*

CMD ["redis-server"]
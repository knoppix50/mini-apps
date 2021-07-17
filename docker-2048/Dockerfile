FROM alpine:latest

MAINTAINER alfredo <knoppix-devops@hotmail.com>

RUN apk --update add nginx
## RUN mkdir /run/nginx

COPY 2048 /var/lib/nginx/html
COPY nginx.conf /etc/nginx

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

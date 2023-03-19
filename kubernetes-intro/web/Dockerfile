FROM ubuntu:18.04

RUN apt update
RUN apt install nginx -y

RUN mkdir -p /app
COPY ./homework.html /app/homework.html
COPY ./default /etc/nginx/sites-available/default

CMD [ "nginx", "-g", "daemon off;" ]

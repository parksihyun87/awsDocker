FROM ubuntu
RUN apt update
RUN apt install -y nginx
WORKDIR /var/www/html
COPY ./webapp/index.html ./index.html

ENTRYPOINT ["nginx", "-g", "daemon off;"]
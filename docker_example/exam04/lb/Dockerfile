FROM nginx
COPY ./conf/nginx.conf /etc/nginx/conf.d/default.conf

ENTRYPOINT ["nginx", "-g", "daemon off;"]
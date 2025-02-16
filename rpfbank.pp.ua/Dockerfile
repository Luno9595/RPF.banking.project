FROM nginx:latest

COPY ./nginx/conf/ /etc/nginx/conf.d/
COPY ./nginx/cert/ /etc/nginx_cert/
COPY ./nginx/website/ /usr/share/nginx/html

EXPOSE 80
EXPOSE 443

CMD ["nginx", "-g", "daemon off;"]

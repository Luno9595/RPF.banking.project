FROM nginx:latest

COPY ./nginx/conf/ /etc/nginx/conf.d/
COPY ./certbot/conf/ /etc/letsencrypt/
COPY ./nginx/website/ /usr/share/nginx/html

EXPOSE 80
EXPOSE 443


CMD ["nginx", "-g", "daemon off;"]

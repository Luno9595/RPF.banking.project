FROM certbot/certbot:latest

COPY ./certbot/conf/ /etc/letsencrypt/
RUN mkdir -p /var/www/certbot

CMD ["sh", "-c", "certbot certonly --webroot -w /var/www/certbot -d rpfbank.pp.ua --email dnikonenok@gmail.com --agree-tos --non-interactive"]

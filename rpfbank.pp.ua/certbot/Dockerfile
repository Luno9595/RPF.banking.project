FROM certbot/certbot:latest

COPY ./certbot/conf/ /etc/letsencrypt/

CMD ["sh", "-c", "certbot certonly --webroot -w /var/www/certbot -d rpfbank.pp.ua --email dnikonenok@gmail.com --agree-tos --non-interactive"]

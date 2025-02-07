FROM certbot/certbot:latest

RUN mkdir -p /var/www/certbot

COPY .certbot/conf/ /etc/letsencrypt/

CMD certbot certonly --webroot -w /var/www/certbot -d rpfbank.pp.ua --email dnikonenok@gmail.com --agree-tos --non-interactive
ENTRYPOINT ["/bin/sh", "-c", "trap exit TERM; while :; do certbot renew; sleep 12h & wait $!; done;"]

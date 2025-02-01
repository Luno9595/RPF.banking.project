FROM certbot/certbot:latest

COPY ./www /var/www/certbot/
COPY ./conf/ /etc/letsencrypt/

CMD ["sh", "-c", "certbot certonly --webroot -w /var/www/certbot -d yourdomain.com --email your-email@example.com --agree-tos --non-interactive && sleep 12h && c>

# Lets Enrypt

This repo contains code to generate a free SSL certificate

This is developed based on: https://phoenixnap.com/kb/letsencrypt-docker

## Useful commands

Command to renew the certificate: `docker-compose run --rm certbot renew`

## Future Direction:

1. Set up a cronjob to automatically renew certificates: https://phoenixnap.com/kb/set-up-cron-job-linux

### Example Command

Dry Run

docker compose run --rm certbot certonly --webroot --webroot-path /var/www/certbot/ --dry-run -d ehrqc.tsonika-lab.cloud.edu.au

Execute

docker compose run --rm certbot certonly --webroot --webroot-path /var/www/certbot/ -d ehrqc.tsonika-lab.cloud.edu.au

This repo contains code to generate a free SSL certificate

This is developed based on: https://phoenixnap.com/kb/letsencrypt-docker

Command to renew the certificate: docker-compose run --rm certbot renew

Future Direction:

1. Set up a cronjob to automatically renew certificates: https://phoenixnap.com/kb/set-up-cron-job-linux

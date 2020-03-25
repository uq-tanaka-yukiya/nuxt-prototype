FROM node:13.10.1-stretch

RUN apt-get update && apt-get install -y \
git \
vim

WORKDIR /var/www/nuxt

ENV HOST 0.0.0.0
EXPOSE 3000

FROM nginx:latest

RUN rm /etc/nginx/conf.d/default.conf
COPY dhparam.pem /etc/nginx/ssl/
COPY nextcloud.key /etc/nginx/ssl/
COPY nextcloud.crt /etc/nginx/ssl/
COPY nextcloud.conf /etc/nginx/conf.d/

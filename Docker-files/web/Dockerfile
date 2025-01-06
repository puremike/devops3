FROM nginx:latest

LABEL "Project"="vprofile"

RUN rm -rf /etc/nginx/conf.d/default.conf

COPY nginxvproapp.conf /etc/nginx/conf.d/vproapp.conf

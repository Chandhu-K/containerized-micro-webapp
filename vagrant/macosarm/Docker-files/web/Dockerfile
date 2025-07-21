FROM nginx
LABEL Author="Chandhu K"
LABEL Version="1.0"
LABEL Description="Dockerfile for Nginx for load balancing for micro-project"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginxmicroapp.conf /etc/nginx/conf.d/microapp.conf
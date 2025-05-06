FROM nginx:latest

RUN rm /etc/nginx/conf.d/default.conf

COPY front-end/softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

COPY front-end/softy-pinko-front-end/ /usr/share/nginx/html/softy-pinko-front-end/

EXPOSE 80

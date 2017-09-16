FROM ubuntu:latest

RUN apt-get update
RUN apt-get install -y python python-dev python-distribute python-pip
RUN apt-get install -y nginx
ADD nginx.conf /etc/nginx/nginx.conf

ADD index.html /var/www/site/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

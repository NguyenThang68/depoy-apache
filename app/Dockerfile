FROM ubuntu
WORKDIR /app
RUN apt-get update
RUN apt -y install apache2

COPY . /var/www/html
ENTRYPOINT apachectl -D FOREGROUND
ENV name Devops Intellipaat
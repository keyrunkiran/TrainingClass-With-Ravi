FROM ubuntu
ADD . /var/www/html/index.html
RUN apt-get update
RUN apt-get install -y apache2
ENTRYPOINT apachectl -D FOREGROUND
EXPOSE 80
ENV name Apache


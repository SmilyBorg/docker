FROM ubuntu:14.04


RUN apt-get -y update && apt-get install -y apache2 libapache2-mod-php5


COPY httpd-foreground /usr/local/bin/

WORKDIR /usr/local/bin/
RUN chmod ugo+x httpd-foreground

EXPOSE 80
CMD ["httpd-foreground"]
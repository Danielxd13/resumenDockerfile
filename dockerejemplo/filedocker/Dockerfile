#from httpd:latest
#copy index.html /usr/local/apache2/htdocs/
#expose 80

FROM debian:latest
RUN apt-get update && apt-get install -y apache2
COPY index.html /var/www/html/
ENTRYPOINT ["/usr/sbin/apache2ctl","-D","FOREGROUND"]


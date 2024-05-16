FROM debian:latest
RUN apt update && apt install -y apache2
RUN mkdir /var/log/apache2/omeusitio.lan
ENTRYPOINT [ "apachectl" , "-D" , "FOREGROUND" ]
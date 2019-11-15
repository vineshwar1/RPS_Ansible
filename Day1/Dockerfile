FROM ubuntu:16.04
MAINTAINER Vineshwar Singh

RUN apt update && apt install -y apache2

EXPOSE 8080

CMD [ "/usr/sbin/apache2ctl", "-D", "FOREGROUND" ]
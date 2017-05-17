FROM ubuntu:trusty
MAINTAINER surya
RUN apt-get update && apt-get -y install apache2 && service apache2 restart
EXPOSE 80
CMD ["ping", "google.com"]

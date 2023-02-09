FROM ubuntu:latest

RUN	apt-get update && \
	apt-get install -y apache2 && \
	apt-get install -y apache2-utils
	
EXPOSE 80

ENTRYPOINT ["apache2ctl"]

CMD ["-DFOREGROUND"]



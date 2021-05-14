FROM debian:buster

RUN		   apt-get update				\
		&& apt-get upgrade				\
		&& apt-get -y install wget		\
		&& wget "http://www.adminer.org/latest.php" -O /var/www/html/adminer.php  

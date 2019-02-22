FROM ubuntu
RUN apt-get update; apt-get -y dist-upgrade; apt-get -y install inetutils-ping traceroute tcptraceroute telnet ssh net-tools wget curl
COPY simpleExec /
CMD ["/simpleExec"]
EXPOSE 8080

FROM ubuntu:20.04

RUN apt-get -y update && apt-get -y install neofetch nano x11-apps

ENV VAR1="HELLO WORLD!!!"

WORKDIR /workspace


#COPY [source] [destination]
COPY example.txt example.txt

CMD ["cat", "example.txt"]

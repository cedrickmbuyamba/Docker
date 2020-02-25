FROM debian

MAINTAINER cmbuyamb <cmbuyamb@student.wtc.co.za>

RUN apt-get update && apt-get install -y cowsay fortune lolcat

ENTRYPOINT /usr/games/fortune | /usr/games/cowsay | /usr/games/lolcat
FROM ubuntu:16.04
LABEL "mantainer"="enumus@gmail.com"

RUN apt update \
    && apt upgrade -y \
    && apt install -y \
    sudo \
    apache2 \
    zip

EXPOSE 80

CMD /bin/bash sudo service apache2 -d
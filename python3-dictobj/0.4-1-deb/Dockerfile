FROM biocontainers/biocontainers:debian-stretch-backports
MAINTAINER biocontainers <biodocker@gmail.com>
LABEL    software="python3-dictobj" \ 
    container="python3-dictobj" \ 
    about.summary="Dictionary where keys can be accessed as instance attributes" \ 
    about.home="http://pypi.python.org/pypi/dictobj" \ 
    software.version="0.4-1-deb" \ 
    version="1" \ 
    about.copyright="2012-2016 William Grim Grim Apps" \ 
    about.license="Apache 2.0" \ 
    about.license_file="/usr/share/doc/python3-dictobj/copyright" \ 
    about.tags=""

ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update && apt-get install -y python3-dictobj && apt-get clean && apt-get purge && rm -rf /var/lib/apt/lists/* /tmp/*
USER biodocker

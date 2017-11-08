FROM phusion/baseimage

RUN apt-get update && apt-get -y upgrade && apt-get install -y alsa

RUN apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

CMD ["/sbin/my_init"]

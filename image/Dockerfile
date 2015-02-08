FROM phusion/baseimage:0.9.16
MAINTAINER Phusion <info@phusion.nl>

ENV HOME /root
ADD . /pd_build
RUN /pd_build/install.sh
RUN gem install rails --no-ri --no-rdoc
CMD ["/sbin/my_init"]
EXPOSE 80 443

FROM ubuntu:12.04
MAINTAINER yves@zioup.com

RUN apt-get update

RUN echo 'deb http://ppa.launchpad.net/svn/ppa/ubuntu precise main' >/etc/apt/sources.list.d/svn.list
RUN apt-key adv --keyserver keyserver.ubuntu.com --recv-key A2F4C039
RUN apt-get update

RUN apt-get install -y subversion
RUN apt-mark hold subversion


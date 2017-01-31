FROM ubuntu

MAINTAINER Swapnil Kulkarni <me@coolsvap.net>

RUN apt-get update \
    && apt-get clean
	
RUN curl -s https://storage.googleapis.com/golang/go1.7.5.src.tar.gz | tar xzvf - -C /usr/local

RUN echo "PATH=\\$PATH:/usr/local/go/bin" > /etc/profile.d/path.sh

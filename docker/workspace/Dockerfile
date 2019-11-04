FROM debian:buster

LABEL maintainer="Leonardo González <ldgonza@gmail.com>"

# Adds work directory
RUN mkdir /var/www
WORKDIR /var/www

# install basic packages
RUN apt-get update && apt-get install -y -q --no-install-recommends \
    zsh \
    git \
    vim \
    curl \
    && apt-get clean
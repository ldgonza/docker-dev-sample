FROM debian:buster
LABEL maintainer="Leonardo González <ldgonza@gmail.com>"

# install basic packages
RUN apt-get update && apt-get install -y -q --no-install-recommends \
    zsh \
    git \
    vim \
    curl \
    && apt-get clean

# Add user for the workspace
RUN useradd -ms /bin/bash workspace
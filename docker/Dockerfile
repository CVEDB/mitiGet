FROM node:10.22.1-buster
LABEL maintainer "Cyber OS Lab."

RUN mkdir /workspace
ADD .git /workspace/.git

WORKDIR /workspace
RUN git reset --hard
RUN apt update
RUN apt install -y nano less tmux zsh vim

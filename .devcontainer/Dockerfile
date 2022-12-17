FROM ubuntu:latest

RUN apt update
RUN apt upgrade

RUN apt install git -y
RUN apt install g++ -y
RUN apt install zsh -y
RUN apt install sudo -y



RUN useradd --create-home --password vscode --shell /bin/zsh vscode
COPY ./.zshrc /home/vscode



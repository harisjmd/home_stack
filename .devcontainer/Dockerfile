FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y software-properties-common git curl  && apt-add-repository -y ppa:ansible/ansible && apt-get update && apt-get install -y ansible
RUN ansible --version
CMD [ "sleep", "infinity" ]
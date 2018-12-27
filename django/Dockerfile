# Dockerfile for Django

FROM python

RUN apt-get update && apt-get upgrade -y

RUN apt-get install -y\

            mysql-client\

            vim

RUN apt-get autoremove && apt-get autoclean

RUN pip install django

RUN pip install mysqlclient

RUN pip install requests

WORKDIR /root

EXPOSE 5000

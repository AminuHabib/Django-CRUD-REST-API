FROM python:3.8-alpine
MAINTAINER Aminu Habib

ENV PYTHONUNBUFFERED 1

WORKDIR /usr/app

COPY ./requirements.txt /requirements.txt
RUN pip install -r /requirements.txt

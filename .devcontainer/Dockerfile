FROM continuumio/miniconda3:4.5.11

#  $ docker build . -t minicondads
#  $ docker run --rm -it minicondads /bin/bash

WORKDIR /code 
COPY requirements.txt .
RUN conda install --yes --file requirements.txt
FROM continuumio/anaconda3
RUN apt update &&\ 
    apt install -y g++
RUN conda install pymc>5
RUN conda install mkl-service &&\
    conda install jupyterlab
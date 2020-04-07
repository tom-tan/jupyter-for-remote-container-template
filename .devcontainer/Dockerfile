FROM continuumio/miniconda3:4.8.2

RUN conda config --add channels defaults \
    && conda config --add channels bioconda \
    && conda config --add channels conda-forge \
    && conda install -y jupyter

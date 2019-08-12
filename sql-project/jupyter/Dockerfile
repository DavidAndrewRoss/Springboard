FROM jupyter/base-notebook

RUN python --version

RUN conda install --quiet --yes -c \
    anaconda mysql-connector-python \
    anaconda tabulate 

VOLUME /notebooks
WORKDIR /notebooks

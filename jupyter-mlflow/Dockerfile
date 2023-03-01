FROM jupyter/datascience-notebook:cde8b4389ade

WORKDIR /home/andreiosgf/

COPY requirements.txt requirements.txt
COPY ejemplo.ipynb ejemplo.ipynb

RUN pip install -r requirements.txt

EXPOSE 8888

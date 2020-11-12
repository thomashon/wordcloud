FROM jupyter/scipy-notebook
COPY requirements.txt .
RUN ["bash", "-c", "source activate root && pip install -r requirements.txt"]


#USER root
#RUN conda install --yes --name root psycopg2
#RUN conda install --yes --name root redis rq
#USER jovyan
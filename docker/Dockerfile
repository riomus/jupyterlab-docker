FROM jupyter/all-spark-notebook

RUN pip install jupyterlab
RUN jupyter serverextension enable --py jupyterlab

COPY start-notebook.sh /usr/local/bin/


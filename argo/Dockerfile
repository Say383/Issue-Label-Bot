FROM python:3.12.0rc3

RUN pip install numpy pandas scikit-learn dill tensorflow dask ktext distributed dask-ml
RUN mkdir /data
RUN mkdir /output
ENV PYTHONUNBUFFERED=0
COPY src /src

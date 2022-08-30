FROM tensorflow/tensorflow:2.10.0rc3-gpu

ENV PYTHONPATH=/model/

RUN pip install importlib_resources

COPY wod_latency_submission/ /model/wod_latency_submission/

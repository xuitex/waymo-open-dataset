FROM tensorflow/tensorflow:2.13.0-gpu

ENV PYTHONPATH=/model/

RUN pip install importlib_resources

COPY wod_latency_submission/ /model/wod_latency_submission/

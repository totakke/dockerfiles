FROM python:2.7.18-alpine

LABEL maintainer="Toshiki Takeuchi <roimisia@gmail.com>"

RUN pip install --no-cache-dir papery==0.1.10

WORKDIR /papery

EXPOSE 8000

ENTRYPOINT ["papery"]

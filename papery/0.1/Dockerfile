FROM python:2.7.18-alpine3.11

LABEL maintainer="Toshiki Takeuchi <roimisia@gmail.com>"

ARG PAPERY_VERSION=0.1.10

RUN pip install --no-cache-dir papery==$PAPERY_VERSION

WORKDIR /papery

EXPOSE 8000

ENTRYPOINT ["papery"]

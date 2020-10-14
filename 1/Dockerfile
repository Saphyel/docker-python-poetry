FROM python:3.8-slim

ENV POETRY_VERSION=1.1.3

RUN apt-get update;apt-get install -y curl;rm -rf /var/lib/apt/lists/* \
  ;curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -

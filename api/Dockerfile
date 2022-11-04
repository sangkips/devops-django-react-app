FROM python:3.10-slim

ENV PYTHONUNBUFFERED=1

WORKDIR /api

COPY requirements.txt .

RUN pip install --upgrade pip

RUN pip3 install -r requirements.txt

COPY . .

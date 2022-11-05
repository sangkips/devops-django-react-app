FROM python:3.10-slim

ENV PYTHONUNBUFFERED=1

WORKDIR /api

RUN apt update && apt install -y g++ libpq-dev gcc musl-dev

COPY requirements.txt .

RUN pip install --upgrade pip

RUN pip3 install -r requirements.txt

COPY . .

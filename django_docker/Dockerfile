FROM python:3
# Working Env
ENV PYTHONUNBUFFERED 1
RUN mkdir /app
WORKDIR /app
# Install Django 
COPY requirements.txt /app/
RUN pip install -r requirements.txt 
COPY . /app/




FROM python:3.7-slim

RUN mkdir /app

COPY requirements.txt /app

RUN pip3 install -r /app/requirements.txt --no-cache-dir

COPY . /app

WORKDIR /app

CMD ["sh", "run.sh"]

LABEL author='d4mir.sh.d@yandex.ru' version=1 

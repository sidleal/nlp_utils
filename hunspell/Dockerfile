# cohmetrix
FROM ubuntu:xenial

RUN apt-get update \
    && apt-get install -y python python-pip locales python-dev libhunspell-dev

WORKDIR /opt

COPY . .

RUN pip install --upgrade pip \
    && pip install hunspell

CMD ["python"]


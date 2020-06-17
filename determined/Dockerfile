FROM python:3.7-alpine

RUN pip install determined-cli==0.12.8

RUN mkdir /cmd/
WORKDIR /cmd/

COPY . /cmd/

ENTRYPOINT ["/bin/sh"]

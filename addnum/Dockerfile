FROM python:3-alpine

WORKDIR /zone

RUN apk add --no-cache git && \
    pip install git+https://github.com/hustlemaniac/addnum.git#egg=addnum && \
    apk del git

ENTRYPOINT [ "addnum" ]
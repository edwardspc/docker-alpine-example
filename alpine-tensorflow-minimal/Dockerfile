FROM python:3.6-alpine

RUN apk --no-cache add bash curl gcc g++ make sed zip

COPY tensorflow-1.7.0-cp36-cp36m-linux_x86_64.whl /home/app/

RUN python3 -m pip install --upgrade /home/app/tensorflow-1.7.0-cp36-cp36m-linux_x86_64.whl

FROM python:3.9

COPY ./img2/requirements.txt requirements.txt

RUN apt-get update && \
    apt-get install -y sudo

RUN python --version

RUN echo "### Finish Build ###"
FROM python:3.9.11-buster

COPY ./requirements.txt .
RUN pip install --user -r ./requirements.txt \
    && rm ./requirements.txt
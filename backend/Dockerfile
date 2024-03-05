FROM python:latest
WORKDIR /usr/src/app
ENV PYTHONUNBUFFERED 1
COPY requirements.txt ./backend/
RUN pip install -r ./backend/requirements.txt
COPY . /backend/

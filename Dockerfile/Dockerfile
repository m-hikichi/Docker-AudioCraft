FROM python:3.10

RUN pip install --upgrade pip
COPY requirements.txt .
RUN pip install -r requirements.txt

RUN apt-get update && apt-get install -y ffmpeg

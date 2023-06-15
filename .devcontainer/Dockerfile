FROM python:3.8-slim-buster

WORKDIR /app

ADD . /app

RUN pip install --no-cache-dir torch torchvision torchaudio

EXPOSE 80

CMD ["python", "app.py"]
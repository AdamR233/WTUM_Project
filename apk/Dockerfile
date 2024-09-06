FROM python:3.8-slim

WORKDIR /app

COPY . /app

RUN pip install --default-timeout=100000 -r requirements.txt

CMD ["python", "app.py"]

FROM python:3.12-slim

WORKDIR /app

COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY temperature_subscriber.py .

ENV PYTHONUNBUFFERED=1

CMD ["python", "temperature_subscriber.py"]

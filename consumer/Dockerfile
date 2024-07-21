FROM python:3.8-slim

RUN pip install google-cloud-pubsub psycopg2-binary

WORKDIR /app
COPY consumer.py .
COPY studied-setting-424123-a9-5db97c86a70c.json .

CMD ["python", "consumer.py"]
FROM python:3.8-slim

RUN pip install flask flask-cors google-cloud-pubsub

WORKDIR /app
COPY producer.py .
COPY templates/ templates/
COPY studied-setting-424123-a9-5db97c86a70c.json .

# Expose port
EXPOSE 80

CMD ["python", "producer.py"]
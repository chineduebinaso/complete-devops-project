FROM python:3.9-slim

WORKDIR /app

COPY terraform-configs/app.py .

RUN pip install flask

EXPOSE 8080
CMD ["python", "app.py"]

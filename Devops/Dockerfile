# Base Image
FROM python:3.9-slim

# Working directory
WORKDIR /app

# copy files
COPY app.py .
COPY requirements.txt .

# Install dependencies
RUN pip install --no-cache-dir  -r requirements.txt

# application port
EXPOSE 5000

# run the application
CMD ["python", "app.py"]

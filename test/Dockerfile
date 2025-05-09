# Use official Python image
FROM python:3.11-slim

# Set working directory in container
WORKDIR /app

# Copy requirements file and install
COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

# Copy your application code
COPY . .

# Run the app (update if you use Flask, Django, etc.)
CMD ["python", "main.py"]


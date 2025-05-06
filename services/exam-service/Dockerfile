# Base image
FROM python:3.10-slim

# Set work directory
WORKDIR /app

# Copy requirements and install
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Copy source code
COPY . .

# Expose port and run app (giả sử app chạy trên cổng 5000)
EXPOSE 5000
CMD ["python", "main.py"]

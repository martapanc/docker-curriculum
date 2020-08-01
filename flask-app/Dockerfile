# Specify base image
FROM python:3

# Set a directory for the app
WORKDIR /usr/src/app

# Copy files to the container
COPY . .

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5005

# Run main command
CMD ["python", "./app.py"]
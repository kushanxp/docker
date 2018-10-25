# Use an official Python runtime as a parent image
FROM python:2.7-slim

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents in to the container at /app
COPY . /app

# Install any needed packages specified in requirements.txt	
RUN pip install --trusted-host pypi.python.org -r requirements.txt

# Make port 80 available for the world outside the container
EXPOSE 80

# Define environment variable
ENV Name World

# Run the app.py when the container launches
CMD ["python", "app.py"]
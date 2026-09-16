FROM ubuntu:latest

# Setting the working Directory in the image
WORKDIR /app

# Copy the files to image file syatem 
COPY . /app

#Install the dependecies to run the application
RUN apt-get update&& apt-get install -y python3 python3-pip

# Set environment variables
ENV NAME World

# Run a command to start the application
CMD ["python3", "app.py"]

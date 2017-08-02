#use an official Python runtime as a parent image
From python:2.7-slim

#set the working directory to /app
WORKDIR /app

#copy the current directory contents into the container at /app
ADD . /app

#install any needed packages specified in requirements.txt
RUN pip install -r requirements.txt

#Make port 80 available to the world outside this container
EXPOSE 80

#Define environment variable
ENV NAME world

#Run app.py when the container lunches
CMD ["python","app.py"]

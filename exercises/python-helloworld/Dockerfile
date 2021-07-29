# from label will specify the base image we will use to run application. Python-based image.
FROM python:3.8

# label is used to add metadata to the image
LABEL maintainer="Katie Gamanji"

# copies any file from local host to the container
COPY . /app

# set the working directory
WORKDIR /app

# to run and ensure all the dependencies are installed
RUN pip install -r requirements.txt

# command to run on container start
CMD [ "python", "app.py" ]
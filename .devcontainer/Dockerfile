# use Python slim buster 
FROM python:3.8-slim-buster

# make new project directory
MKDIR /project

# make project folder current working directory
WORKDIR /project

# copy requirements file to container
COPY requirements.txt .

# install requirements
RUN pip install -r requirements.txt


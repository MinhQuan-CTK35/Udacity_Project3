FROM python:3.10-slim-buster

USER root

WORKDIR /src

COPY ./requirements.txt requirements.txt

# Install any needed packages specified in requirements.txt
RUN pip install --trusted-host pypi.python.org -r requirements.txt

COPY . .

CMD python app.py

# Base image (os)

FROM python:3.7

# working Directory

WORKDIR /APP

# Code copy

COPY . /APP

# Install libraries

RUN pip install -r requirements.txt

# Migrate server

RUN python cool_counters/manage.py migrate

#run app

CMD ["python","cool_counters/manage.py","runserver","0.0.0.0:8000"]

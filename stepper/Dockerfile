FROM python:3.8

WORKDIR /app

COPY requirements.txt . 

RUN pip install -r requirements.txt

COPY app/ . 

# For production
# CMD ["python", "./app.py"]

# For testing
CMD ["tail", "-f", "/dev/null"]
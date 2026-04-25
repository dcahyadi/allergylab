FROM python:3.14.4-alpine3.23

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD ["python","-u","loader.py"]
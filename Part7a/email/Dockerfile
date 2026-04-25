FROM python:3.14.4-alpine3.23

COPY . /app
WORKDIR /app
# RUN apt-get update && apt-get install -y sendmail
RUN pip install -r requirements.txt
ENTRYPOINT [ "python" ]
CMD [ "mailsender.py" ]
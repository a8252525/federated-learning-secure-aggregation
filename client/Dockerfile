FROM python:3.6

WORKDIR /client

COPY ./requirements.txt /requirements.txt

# ADD requirements.txt .
RUN pip install -r /requirements.txt

# ADD app .
COPY ./app /app

ENV SERVER_IP='http://140.113.164.36:3000'

ENTRYPOINT ["python"]

CMD ["/app/client.py"]

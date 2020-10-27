FROM python:3.6

WORKDIR /client

COPY ./requirements.txt /requirements.txt

# ADD requirements.txt .
RUN pip install -r /requirements.txt

# ADD app .
COPY ./app /app

ENTRYPOINT ["python"]

CMD ["/app/client.py"]

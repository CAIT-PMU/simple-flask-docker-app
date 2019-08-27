FROM python:3.6

ADD . /app

WORKDIR /app

RUN pip install flask
Run pip install gunicorn

Expose 8000

CMD ["gunicorn", "-b", "0.0.0.0:8000", "app"]

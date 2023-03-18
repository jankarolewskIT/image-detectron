FROM python

WORKDIR /app/

COPY requirements.txt /app

RUN pip install -r /app/requirements.txt

COPY . /app

CMD ["python", "/app/manage.py", "runserver", "0.0.0.0:8000"]

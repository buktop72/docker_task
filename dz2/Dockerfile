FROM python:3.9

WORKDIR stocks_products

COPY ./stocks_products /stocks_products

RUN pip install -r /stocks_products/requirements.txt



RUN python manage.py migrate

CMD ["python", "/stocks_products/manage.py", "runserver", "0.0.0.0:8000"]



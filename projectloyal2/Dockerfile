FROM python:3.8

WORKDIR /projectloyal2

COPY requirements.txt /projectloyal2/
RUN pip install --no-cache-dir -r requirements.txt

COPY . /projectloyal2/

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]

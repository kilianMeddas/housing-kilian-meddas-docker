FROM python:3.11

COPY app_migration.py .
COPY create_db.py .
COPY requirements.txt . 

RUN pip3 install -r requirements.txt

CMD ["python", "create_db.py", "app_migration"]

FROM python:#

COPY requirements.txt /requirements.txt 

RUN pip install -r requirements

COPY deployment.py /deployment.py

CMD ["python", "/deployment.py"]

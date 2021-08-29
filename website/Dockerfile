FROM python:3.7.9

WORKDIR C:/Users/ardau/Documents/GitHub/deploy/website

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

CMD [ "python", "./app.py" ]
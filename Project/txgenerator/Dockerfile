FROM python:3.7-buster

WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip3 install --no-cache-dir -r requirements.txt

COPY app.py ./

CMD [ "python3", "./app.py" ]
FROM python:3.9

WORKDIR /app

COPY ./requirements.txt /app/requirements.txt

RUN pip install --upgrade pip
RUN pip3 install -r /app/requirements.txt

CMD fastapi run --reload
# python project
FROM python:3.13-alpine

WORKDIR /app

COPY ./requirements.txt .
RUN pip install -r requirements.txt

COPY ./ .

EXPOSE 5050
ENTRYPOINT [ "python", "app/app.py" ]

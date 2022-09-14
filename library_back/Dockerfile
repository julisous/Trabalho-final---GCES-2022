FROM python:latest

WORKDIR /app/library_back

COPY ./requirements.txt .

COPY . .

RUN pip install -r requirements.txt 

EXPOSE 8080

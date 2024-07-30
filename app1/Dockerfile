#FROM python:3.8

#EXPOSE 8080
#WORKDIR /app

#COPY . ./

#RUN pip install -r requirements.txt

#CMD ["python", "app.py"]

FROM ubuntu:18.04
RUN apt-get update
RUN apt-get install nginx -y
COPY index.html /var/www/html/
EXPOSE 80
CMD ["nginx","-g","daemon off;"]

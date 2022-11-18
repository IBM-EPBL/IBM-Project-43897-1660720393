# FROM python:3.9
# WORKDIR /app
# ADD . /app
# COPY requirements.txt /app
# RUN python3 -m pip install -r requirements.txt
# EXPOSE 3000
# CMD ["python","app.py"]

  FROM python:3.9
  LABEL maintainer="Kunal Malhotra, kunal.malhotra1@ibm.com"
  RUN apt-get update
  RUN mkdir /app
  WORKDIR /app
  COPY . /app
  RUN pip install -r requirements.txt
  EXPOSE 5000
  ENTRYPOINT [ "python" ]
  CMD [ "app.py" ]

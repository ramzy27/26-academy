FROM python:2.7-slim
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
CMD [ "python", "__main__.py", "-Hdb","-P 27017", "-DesanteDB","-uadmin", "-p admin", "-Aweb" ]

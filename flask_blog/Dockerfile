# start from base
FROM python:alpine 
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt 
EXPOSE 8080 
ENTRYPOINT [ "python" ] 
CMD [ "app.py" ] 


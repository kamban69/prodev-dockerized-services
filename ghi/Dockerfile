FROM python:3

WORKDIR /usr/src/server

COPY server.py ./

COPY . .
EXPOSE 80
CMD [ "python", "./server.py" ]
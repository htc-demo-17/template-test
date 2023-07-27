FROM registry.hub.docker.com/library/python:3.12-rc-slim-bookworm
WORKDIR /app
RUN pip3 install flask
COPY . /app
EXPOSE 5000
ENTRYPOINT ["python3","app.py"]

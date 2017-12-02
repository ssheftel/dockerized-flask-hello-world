# dockerized-flask-hello-world
simple flask hello world app running in docker container

# Commands

- run the app locally: `python app.py`
- build docker image: `docker build -t dockerizedflaskhelloworld:latest .`
- create container from image: `docker run -d -p 5000:5000 dockerizedflaskhelloworld`

FROM ubuntu:latest

RUN apt-get update && apt-get install -y python

COPY hello_world.py /hello_world.py

ENTRYPOINT python hello_world.py

# docker build -t hello-world ./hello-world
# docker run hello-world -rm
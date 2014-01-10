docker-go
=========

Docker image for running go apps

```
FROM ubuntu:12.04
RUN apt-get update
RUN apt-get install -y python-software-properties git
RUN add-apt-repository -y ppa:duh/golang
RUN apt-get update
RUN apt-get install -y golang
```
FROM ubuntu:latest
RUN apt-get update && apt-get -y upgrade
RUN apt-get install -y openjdk-17-jre
COPY . ./server
WORKDIR ./server
ENTRYPOINT ["sh", "./run.sh"]

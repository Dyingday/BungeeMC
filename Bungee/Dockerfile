FROM ubuntu:latest
RUN apt-get update && apt-get -y upgrade
RUN apt-get install -y openjdk-17-jre
COPY . ./proxy
WORKDIR ./proxy
EXPOSE 25577
CMD ["./run.sh"]

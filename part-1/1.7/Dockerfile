FROM ubuntu:16.04

WORKDIR /1.7
COPY ./1.7.sh /
RUN ["chmod", "+x", "/1.7.sh"]
RUN apt-get update -y && apt-get install -y curl
CMD ["sh", "-c", "/1.7.sh"]

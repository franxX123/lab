FROM ubuntu:24.04

WORKDIR /app

COPY . .

RUN chmod 700 greet.sh

ENV GREETING="Howdy"
ENV NAME="Francis"

CMD ["./greet.sh"]

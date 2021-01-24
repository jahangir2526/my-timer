FORM ubuntu
RUN apt-get update && apt-get install inetutils-ping vim -y

COPY timer.sh /opt/
ENTRYPOINT /opt/timer.sh

FROM bitnami/java:latest

WORKDIR /app

COPY app.java .

RUN javac app.java

CMD java app; tail -f /dev/null

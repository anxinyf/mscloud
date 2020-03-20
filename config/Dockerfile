FROM java:8-jre
MAINTAINER anxinyf

ADD ./target/config-service-0.0.1-SNAPSHOT.jar /app.jar

CMD ["java", "-Xmx200m", "-jar", "/app.jar"]

EXPOSE 8888

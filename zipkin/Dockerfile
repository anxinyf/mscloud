FROM java:8-jre
MAINTAINER anxinyf

ADD ./target/zipkin-service-0.0.1-SNAPSHOT.jar /app.jar

CMD ["java", "-Xmx200m", "-jar", "/app.jar", "--spring.profiles.active=dev"]

EXPOSE 3000

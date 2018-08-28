FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY build/libs/gs-spring-boot-0.1.0.jar app.jar
ENV JAVA_OPTA=""
ENTRYPOINT ["sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /app.jar"]


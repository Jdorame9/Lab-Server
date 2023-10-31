FROM openjdk:11
WORKDIR /app
COPY app.jar /app/app.jar
COPY application.properties /app/application.properties
CMD ["java", "-jar", "app.jar", "--spring.config.location=/app/application.properties"]
FROM eclipse-temurin:21-jdk-alpine
COPY target/*.jar /app/ewm-service.jar
WORKDIR /app
ENTRYPOINT ["java", "-jar", "ewm-service.jar"]

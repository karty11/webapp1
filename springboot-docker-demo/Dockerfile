FROM eclipse-temurin:17
LABEL authors="karty"
WORKDIR /app
COPY target/springboot-docker-demo-0.0.1-SNAPSHOT.jar /app/springboot-docker-demo.jar
EXPOSE 3000
ENTRYPOINT ["java", "-jar", "springboot-docker-demo.jar"]

# Use OpenJDK base image
# Change line 2 to use Eclipse Temurin (highly recommended)
FROM eclipse-temurin:17-jdk-jammy    # Full JDK via Eclipse Temurin


WORKDIR /app

COPY target/java-jenkins-docker-1.0-SNAPSHOT.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]




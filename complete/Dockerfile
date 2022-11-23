FROM openjdk:8-jdk-alpine
RUN addgroup -S spring && adduser -S spring -G spring
USER spring:spring
COPY build/libs/complete-0.0.1-SNAPSHOT.jar /app/lib/
ENTRYPOINT ["java","-jar","/app/lib/complete-0.0.1-SNAPSHOT.jar"]

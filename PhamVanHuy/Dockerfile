FROM eclipse-temurin:22-jdk

WORKDIR /app

COPY PhamVanHuy/target/*.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar","--server.port=8080","--server.address=0.0.0.0"]
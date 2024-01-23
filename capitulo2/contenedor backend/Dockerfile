#DockerFile backend
FROM openjdk:11
WORKDIR /app
COPY backend.jar .
EXPOSE 9091
ENTRYPOINT ["java","-jar","backend.jar"]

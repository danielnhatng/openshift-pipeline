FROM 10.98.86.97:8082/openjdk:21-ea-17-slim-buster
WORKDIR /app
ARG JAR_FILE=./target/*.jar
COPY ${JAR_FILE} ./app.jar
EXPOSE 8080
CMD [ "sh","-c","java -jar /app/app.jar"]
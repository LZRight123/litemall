FROM openjdk:8-jre
WORKDIR /app
COPY application.yml /app/application.yml
COPY ./litemall.jar /app/litemall.jar
ENTRYPOINT ["java", "-jar","litemall.jar"]

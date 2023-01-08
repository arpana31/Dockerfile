FROM openjdk:8
EXPOSE 3000
ADD target/docker.jar docker.jar
ENTRYPOINT ["java","-jar","docker.jar"]

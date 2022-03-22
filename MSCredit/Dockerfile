FROM openjdk:8-jdk-alpine
ADD target/*.jar /usr/share/ms-credit.jar
EXPOSE 8092
ENTRYPOINT ["java", "-jar", "/usr/share/ms-credit.jar"]
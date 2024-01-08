FROM openjdk:17
WORKDIR /work/

COPY target/*.jar /work/orphins.jar

EXPOSE 8080
CMD ["java","-jar","orphins.jar"]
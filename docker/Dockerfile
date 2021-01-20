FROM openjdk:8
VOLUME /date/eureka
ADD eureka-0.0.1-SNAPSHOT.jar eureka.jar
EXPOSE 8091
ENTRYPOINT ["java","-jar","/eureka.jar"]

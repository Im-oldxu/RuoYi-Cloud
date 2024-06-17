FROM openjdk:8-jre-alpine

COPY ./target/*.jar /ruoyi-auth.jar

EXPOSE 9200
ENTRYPOINT ["java","-jar","/ruoyi-auth.jar"]

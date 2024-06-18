FROM uhub.service.ucloud.cn/oldxu/openjdk:8-jre
COPY ./target/*.jar /ruoyi-gateway.jar

EXPOSE 8080
ENTRYPOINT ["java","-jar","/ruoyi-gateway.jar"]

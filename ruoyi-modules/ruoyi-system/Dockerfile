FROM uhub.service.ucloud.cn/oldxu/openjdk:8-jre-alpine

COPY ./target/*.jar /ruoyi-modules-system.jar

EXPOSE 9201
ENTRYPOINT ["java","-jar","/ruoyi-modules-system.jar"]

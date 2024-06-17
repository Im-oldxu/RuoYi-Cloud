FROM openjdk:8-jre

COPY ./target/*.jar /ruoyi-monitor.jar
RUN mkdir -p /app/logs/

EXPOSE 9100
#ENTRYPOINT ["java","-jar","/ruoyi-monitor.jar"]
ENTRYPOINT ["/bin/bash","-c"," java -jar /ruoyi-monitor.jar | tee -a /app/logs/monitor.log"]

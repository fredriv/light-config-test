FROM openjdk:8-jre-alpine
ADD ./service/hybrid-query.jar server.jar
CMD ["/bin/sh","-c","java -Dlight-4j-config-dir=/config -Dlogback.configurationFile=/config/logback.xml -cp /server.jar:/service/* com.networknt.server.Server"]

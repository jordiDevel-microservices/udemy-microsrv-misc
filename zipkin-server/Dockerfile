FROM openjdk:8-slim
VOLUME /tmp
EXPOSE 9411
ADD ./zipkin-server-2.21.1-exec.jar zipkin-server.jar
ENTRYPOINT ["java", "-jar", "/zipkin-server.jar"]

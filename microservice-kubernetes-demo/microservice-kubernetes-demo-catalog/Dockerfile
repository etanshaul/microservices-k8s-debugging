FROM openjdk:10.0.2-jre-slim
ENV JAVA_TOOL_OPTIONS=-agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=5005,quiet=y
COPY target/microservice-kubernetes-demo-catalog-0.0.1-SNAPSHOT.jar .
CMD /usr/bin/java -Xmx400m -Xms400m -jar microservice-kubernetes-demo-catalog-0.0.1-SNAPSHOT.jar
EXPOSE 8081

FROM ewolff/docker-java
ADD target/microservice-demo-turbine-server-0.0.1-SNAPSHOT.jar .
CMD /usr/bin/java -Xmx400m -Xms400m -Djava.security.egd=file:/dev/./urandom -jar microservice-demo-turbine-server-0.0.1-SNAPSHOT.jar
EXPOSE 8989
FROM java:8
VOLUME /tmp
ADD seata-server-1.3.0.jar seata-server.jar
EXPOSE 8091
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/seata-server.jar"]
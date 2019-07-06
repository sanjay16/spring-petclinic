FROM java:8-alpine
VOLUME /tmp
RUN sh -c 'touch /hello-boot.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/springboot-petclinic-1.4.1.jar"]

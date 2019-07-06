FROM java:8-alpine
VOLUME /tmp
ARG JAR_FILE
ADD ./target/${JAR_FILE} /springboot-petclinic-1.4.1.jar
RUN sh -c 'touch /hello-boot.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/springboot-petclinic-1.4.1.jar"]
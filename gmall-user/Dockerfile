FROM openjdk-8-jdk-alpine
VOLUME /tmp
COPY ./target/demojenkins.jar demojenkins.jar
WORKDIR /liveboard-tests
ENTRYPOINT ["java","-jar","/demojenkins.jar","&"]
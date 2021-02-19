FROM ascdc/jdk8:latest as jdk8
RUN mkdir -p /var/target
WORKDIR /var/target
COPY spring-petclinic-2.4.2.jar /var/target
EXPOSE 8080
CMD ["java", "-jar", "target/*.jar"]

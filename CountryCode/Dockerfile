FROM openjdk:11
COPY  ./target/CountryCode-0.0.1-SNAPSHOT.jar /usr/app/
WORKDIR /usr/app
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "CountryCode-0.0.1-SNAPSHOT.jar"]
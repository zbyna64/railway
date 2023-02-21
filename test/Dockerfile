FROM openjdk:8
COPY --from=build /build/libs/test-0.0.1-SNAPSHOT-plain.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
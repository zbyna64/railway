#FROM openjdk:8
#COPY --from=build /build/libs/test-0.0.1-SNAPSHOT-plain.jar app.jar
#ENTRYPOINT ["java", "-jar", "app.jar"]



#Build stage
#
#FROM gradle:latest AS BUILD
#WORKDIR /usr/app/
#COPY . .
#RUN gradle build
#
## Package stage
#
#FROM openjdk:8
#ENV JAR_NAME=test-0.0.1-SNAPSHOT-plain.jar
#ENV APP_HOME=/usr/app/
#WORKDIR $APP_HOME
#COPY --from=BUILD $APP_HOME .
#EXPOSE 8080
#ENTRYPOINT exec java -jar $APP_HOME/build/libs/$JAR_NAME
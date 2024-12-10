FROM eclipse-temurin:17
RUN mkdir /opt/app
COPY build/libs/docker-test-app-0.0.1-SNAPSHOT.jar /opt/app/cjmin_app.jar
CMD ["java", "-jar", "/opt/app/cjmin_app.jar"]
EXPOSE 8888
#명시적인 것이고 강제성을 가지지않음

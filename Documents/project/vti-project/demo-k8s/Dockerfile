FROM openjdk:8-jdk-alpine
COPY src/Main.java /app/Main.java
WORKDIR /app
RUN javac Main.java
CMD ["java", "Main"]
FROM openjdk:8
COPY src/game/guess.java /tmp
WORKDIR /tmp
RUN ["javac","guess.java"]
ENTRYPOINT  ["java","guess"]
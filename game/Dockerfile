FROM openjdk:8
COPY game2/src/game/guess.java /tmp
WORKDIR /tmp
RUN ["javac","guess.java"]
ENTRYPOINT  ["java","guess"]

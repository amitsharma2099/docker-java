#Command to build this project from docker terminal: docker build -t docker-java .
FROM java:8
WORKDIR /app
#COPY Test.java .
ADD Test.java .
RUN javac Test.java
CMD ["java", "Test"]
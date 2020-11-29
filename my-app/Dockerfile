FROM java:8
WORKDIR /
ADD https://dev.azure.com/oristar/Hello%20World/_build/results?buildId=5&view=artifacts&pathAsName=false&type=publishedArtifacts/my-app-1.0-SNAPSHOT.jar my-app-1.0-SNAPSHOT.jar
EXPOSE 8080
CMD java -jar my-app-1.0-SNAPSHOT.jar

FROM openjdk:10-jre-slim

ENV MARPLE_VERSION=1.0

RUN apt-get update && apt-get install -y wget

RUN wget --quiet -O /marple.jar https://github.com/flaxsearch/marple/releases/download/v${MARPLE_VERSION}/marple-${MARPLE_VERSION}.jar

EXPOSE 8080

CMD ["java", "--add-modules", "java.xml.bind", "-Ddw.indexPath=/index", "-jar", "marple.jar", "server"]

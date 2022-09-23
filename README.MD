# Apache Flink template

## Setup local by using Docker Compose
```bash
docker-compose up
```

## Execute into Master or Worker
```bash
# Master
docker exec -it flink-master bash
# Worker
docker exec -it flink-worker bash
```

## Combine Job with Maven
```bash
# Build flink job and skip tests by using
# Must contain and config the pom.xml file
mvn clean install -DskipTests
```

## Combine Job with SBT
```bash
sbt assembly
```


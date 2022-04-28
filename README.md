# Project Builder
Test build project with use Maven and Gradle scripts

## Requirements:
* JDK 11
* Apache Maven
* Gradle

## Build application: Maven
start only tests
```
mvn clean test
```
build project
```
mvn clean install
```
to start web-app
```
mvn jetty:run
```
It runs application for web-app via host [http://localhost:8082](http://localhost:8082)

## Build application: Gradle
start only tests
```
./gradlew clean test
```
build project
```
./gradlew clean build
```

# bootstrap-java8-archetype

The project is a Maven archetype for to generate a Java project with JUnit 5 and AssertJ dependencies

## Prerequisites

- JDK 8+
- Maven 3

## Install archetype

First, you need to compile and install the archetype in your local repository or eventually push to a public or private one:

```bash
    git clone https://github.com/newlight77/bootstrap-java-archetype.git
    cd bootstrap-java-archetype
    mvn clean install
```

## Use

Create a project using the archetype :
 
```bash
 mvn archetype:generate \
 -DarchetypeGroupId=com.newlight77 \
 -DarchetypeArtifactId=bootstrap-java-archetype \
 -DarchetypeVersion=1.0-SNAPSHOT  \
 -DgroupId=com.example       \
 -DartifactId=java-project      \
 -DinteractiveMode=false
```

# About #

Java console application to be used as starting point in a Scrum workshop. If you know maven, you'll be familiar with the project structure. The only unfamiliar thing is that the main package was shortened just to `callsprocessor` to reduce typing.

# Tools and Prerequisites #
This project was created using `Apache Maven 3` quickstart archetype [Maven Quickstart Archetype](https://maven.apache.org/archetypes/maven-archetype-quickstart/). So you need to install maven 3 in order to handle common build tasks.

# Common Tasks #

1. Compile the project : `mvn compile`
2. Compile and run tests: `mvn test`
3. Run the console application: `mvn exec:java -Dexec.mainClass=callsprocessor.App`
4. Run the console application with arguments: `mvn exec:java -Dexec.mainClass=callsprocessor.App -Dexec.args="We came from console"`
5. Run console app from jar file `java -cp callsprocessor-<version>.jar callsprocessor.App Some Console Args`
6. Simulate CI build: `mvn -B verify`
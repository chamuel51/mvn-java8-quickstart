# About #

Java console application to be used as starting point in a Scrum workshop. If you know maven, you'll be familiar with the project structure. The only unfamiliar thing is that the main package was shortened just to `callsprocessor` to reduce typing.

# Tools and Prerequisites #
This project was created using `Apache Maven 3` quickstart archetype [Maven Quickstart Archetype](https://maven.apache.org/archetypes/maven-archetype-quickstart/). So you need to install maven 3 in order to handle common build tasks. You also need Java JDK 8 or later. Before starting you need all the following three programs on our path: mvn, java, javac. Test those with:
* `mvn --version`
* `java -version`
* `javac -version`

You can get Maven 3 from:
* Apache direct download for your OS [Downloading Apache Maven 3.6.3](https://maven.apache.org/download.cgi)
* Chocolatey for Windows users: [Maven
3.6.3 @ Chocolatey](https://chocolatey.org/packages/maven)
* Brew for MacOS users [Homebrew Formulae Maven](https://formulae.brew.sh/formula/maven#default)

## IDE ##
The project can be edited with a simple editor like [Visual Studio Code](https://code.visualstudio.com/download), with Java plugins installed, Alternatively you can use the pre-package installer with Java Plugins:  [Installer of Visual Studio Code for Java developers](https://aka.ms/vscode-java-installer-win). Remember that Eclipse and IntelliJ IDEA consume a lot of system resources.

# Common Tasks #

1. Compile the project : `mvn compile`
2. Compile and run tests: `mvn test`
3. Run the console application: `mvn exec:java -Dexec.mainClass=callsprocessor.App`
4. Run the console application with arguments: `mvn exec:java -Dexec.mainClass=callsprocessor.App -Dexec.args="We came from console"`
5. Run console app from jar file `java -cp callsprocessor-<version>.jar callsprocessor.App Some Console Args`
6. Simulate CI build: `mvn -B verify`
# SDET Poker Hand Evaluator Assignment

### Getting Started

1. Download and install [OpenJDK 11 (LTS)](https://adoptopenjdk.net/)
    - On the Custom Setup step during installation, enable `Set JAVA_HOME variable`
2. Download and install [IntelliJ Idea Community Edition](https://www.jetbrains.com/idea/download)
3. Launch IntelliJ Idea and follow first time set up, default settings are fine
4. Select `Open or Import`
5. Navigate to and select the project directory 

### Project Structure
The implementation of the project can be found in `src/main/java/net/covasoft/poker`
Test cases should be written in 
- `src/test/java/net/covasoft/poker/HandTest.java`
- `src/test/java/net/covasoft/poker/PokerTest.java`

### Running Tests
Implemented tests can be run through the IDE, with `gradlew test` or `./gradlew test`
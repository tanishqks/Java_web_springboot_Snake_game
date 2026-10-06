# Snake Game - Java Spring Boot

This is a browser-based Snake Game where the application itself is built with Java Spring Boot.

## Requirements

- JDK 17 or newer
- Maven 3.9+ OR use the included Maven Wrapper if added later
- VS Code / IntelliJ / Eclipse

## Project structure

src/main/java/com/example/snakegame/
- SnakeGameApplication.java
- GameController.java

src/main/resources/templates/
- index.html

## Run in VS Code

Open the terminal in the project folder.

### Maven

Windows:
mvn spring-boot:run

If Maven is not installed:
- Install Maven, or
- Open the project in an IDE with Spring Boot/Maven support.

### Build a JAR

mvn clean package

Then:

java -jar target/snake-game-1.0.0.jar

## Open the game

After Spring Boot starts, open:

http://localhost:8080

## Important

The game logic is served from a Java Spring Boot application. The browser still needs HTML/CSS/JavaScript to display the game and read keyboard input; Spring Boot is the Java web backend/framework.

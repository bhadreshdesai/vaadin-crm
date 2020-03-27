# Project Base for Vaadin and Spring Boot

This project can be used as a starting point to create your own Vaadin application with Spring Boot.
It contains all the necessary configuration and some placeholder files to get you started.

The best way to create your own project based on this starter is [start.vaadin.com](https://start.vaadin.com/) - you can get only the necessary parts and choose the package naming you want to use.

## Running the Application

Import the project to the IDE of your choosing as a Maven project.

Run the application using `mvn spring-boot:run` or by running the `Application` class directly from your IDE.

Open http://localhost:8080/ in your browser.

If you want to run the application locally in the production mode, run `mvn spring-boot:run -Pproduction`.

To run Integration Tests, execute `mvn verify -Pintegration-tests`.

## More Information

- [Vaadin Flow](https://vaadin.com/flow) documentation
- [Using Vaadin and Spring](https://vaadin.com/docs/v14/flow/spring/tutorial-spring-basic.html) article

## IntelliJ configuration for live reload
Using Ctrl+Shift+A (or ⌘+Shift+A on Mac) type Registry once the registry windows is open, locate and enable compiler.automake.allow.when.app.running

For some reason this option is not available in IntelliJ 2019.3

File->Settings->Compiler

Enable "Build project automatically"

## H2 Console
H2 database console is available at http://localhost:8080/h2-console

Use jdbc:h2:mem:testdb as JDBC URL and click Connect

You should see COMPANY and CONTACT table populated with data



# Basic example of Vaadin Form with Spring Boot & Spring Data

The example contains a view that submits competition registrations. The UI is similar to what you might have seen in Vaadin expo booth. 

<img src="https://raw.githubusercontent.com/vaadin/registration-example/master/screenshot.png" alt="Registration example app" title="Registration example app" width="50%">

In addition this version submits the registrations to a [JPA backend](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/), validates the data automatically based on [JSR-303 annotations](https://beanvalidation.org/specification/) in the domain object and also contains a view to list current submissions.

## Clone and run the app

You can use it as a basis for your Vaadin experiments. To play around with the example, check it out using git or download the zip. Import it to your favorite IDE and execute the Application class or start the app from command line using: 

    git clone https://github.com/vaadin/registration-example.git
    or
    git@github.com:wallaceespindola/vaadin-spring-boot-data-registration-page.git
    cd registration-example
    mvn spring-boot:run

The application opens to http://localhost:8080

## Where to go from here? 

There is a tutorial about Creating CRUD UI with Vaadin at https://spring.io/guides/gs/crud-with-vaadin/
and for more complete Vaadin examples, visit http://vaadin.com/start 

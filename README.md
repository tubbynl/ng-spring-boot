# Demo using Spring Boot and AngularJS
This example demonstrates how **Spring Boot**, **Spring Data JPA** and in the front-end **AngularJS** can be used together to write web applications easily.
In this code example I'm demonstrating this by providing a full CRUD-based web application in about 150 lines of code.

## Frameworks

### Front-end

#### Twitter Bootstrap
For rapidly creating prototypes of a web application, a UI toolkit or library will become really handy. There are many choices available, and for this example I chose Twitter Bootstrap.

#### AngularJS
AngularJS is a MVC based framework for web applications, written in JavaScript. It makes it possible to use the Model-View-Controller pattern on the front-end. It also comes with several additional modules. In this example I'm also using **angular-resource**, which is a simple factory-pattern based module for creating REST clients.

### Back-end

#### Spring Boot
One of the hassles while creating web applications using the Spring Framework is that it involves a lot of configuration. Spring Boot makes it possible to write configuration-less web application because it does a lot for you out of the box.

#### Spring Data JPA
Spring Data JPA allows you to create repositories for your data without even having to write a lot of code. The only code you need is a simple interface that extends from another interface and then you're done.
With Spring Boot you can even leave the configuration behind for configuring Spring Data JPA, so now it's even easier.

## Build
Building is quite easy, first you run Gradle to package the application:
```
gradle build
```

Now you can run the jar:
```
java -jar build/libs/Todo-0.0.1-SNAPSHOT.jar
```

Or run the TodoApplication class as Java application from within an IDE
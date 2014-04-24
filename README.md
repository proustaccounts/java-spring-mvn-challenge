java-spring-mvn-challenge
=========================

A challenge to build a spring and maven based java project

## Java Programming Task

This is a challenge to build a spring and maven based java project. You must complete the following steps. 

*Note: Depending on your skill and experience level this task may take anywhere from 2 hours to a week (a full 40 hour working week).*


### Prerequisites

- Please note that this will require some basic [Java](http://docs.oracle.com/javase/tutorial/), [Maven](http://maven.apache.org/), [Spring](http://spring.io/) and [Git](http://git-scm.com/documentation) knowledge. 

- While not required, it is recommended you install and use an IDE like [Eclipse](https://www.eclipse.org/downloads/packages/eclipse-ide-java-ee-developers/keplersr2) or [IntelliJ](http://www.jetbrains.com/idea/). 

## Task

1. Fork this repository (if you don't know how to do that, Google is your friend)
2. Create a maven project to manage your build and project dependencies like spring libraries:
  - configure maven so that the application is easily started from the command line; one example is to setup the maven jetty plugin so that the command "mvn jetty:run" starts the application on port 8080 
3. Set up a Spring MVC application which runs on port 8080 and achieves all of the following when the http://localhost:8080/spring-commits/ URL is accessed:
	- Connect to the [Github API](http://developer.github.com/)
	- Find the [spring-projects/spring-framework](https://github.com/spring-projects/spring-framework) repository
	- Find the most recent 40 commits.
	- Create and return an HTML page with a table displaying the recent commits by author. For each author include their full name and e-mail address. For each comit include the hash and the html URL.
	- If the commit hash ends in a number, color that row to light blue (#E6F1F6).

### Tests

Create the following unit test with the testing framework of your choice. Running "mvn test" on the command line should run all tests and show them as passing:

  1.  Verify that rows ending in a number are colored light blue.  

## Once Complete
1. Commit and Push your code to your new repository
2. Send us a pull request. We will review your code and get back to you. 

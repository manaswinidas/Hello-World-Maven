# Hello-World-Maven

This is a Hello World site built with Java and Maven. 

In order to run this in your local system, make sure that you have [Maven](https://maven.apache.org/) and [Java](https://www.java.com/en/download/) installed.
Clone this repository.

## Build and Run the project

`cd Hello-World-Maven`
`mvn package`

You may test the newly compiled and packaged JAR with the following command:
`java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App`

This will print:
`Hello World!`

## Generate the site
`mvn site`
`mvn site:run`

# Scheduling Tasks

This is a Spring Boot application designed to schedule and execute tasks periodically. The application demonstrates how to use the Spring Framework’s `@Scheduled` annotation to create scheduled tasks that run automatically at regular intervals.

## Features

- **Periodic Task Execution**: The application prints the current time to the console every 5 seconds.
- **Simple Scheduling with `@Scheduled`**: Task scheduling is configured in a simple and efficient way using Spring annotations.
- **Automated Tests for Scheduled Tasks**: Tests are included to ensure the scheduled tasks run correctly.

## Technologies Used

- **Java 17**: The latest stable version for development.
- **Spring Boot**: A framework for building Java applications quickly and efficiently.
- **JUnit 5**: For writing and running tests.
- **Mockito**: For mocking dependencies and interactions in tests.
- **Awaitility**: For verifying asynchronous operations in tests.
- **SLF4J**: For simple and effective logging.

## Getting Started

### Prerequisites

Before running this application, ensure you have the following installed:

- **Java 17** or later
- **Maven**

## Installing the project
First you must clone the repository.
```bash
# clone repository
$ git clone https://github.com/herikerbeth/scheduling-tasks.git

# enter the project folder
$ cd scheduling-tasks
```

Now, inside IntelliJ, we will install the dependencies with Maven

<img width="300px" src="https://github.com/herikerbeth/assets/blob/main/install-dependencies.png?raw=true">

## Starting
Finally, navigate to the Application class file to run the project.

<img width="300px" src="https://github.com/herikerbeth/assets/blob/main/run-application.png?raw=true">

## Test the Service
The project includes an automated test to ensure the scheduled task runs correctly, run the integration test:

```bash
$ mvn test
```

## Source
Based on the official Spring documentation from [Spring.io](https://spring.io/guides/gs/scheduling-tasks).
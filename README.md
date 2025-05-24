# Cloud Functions AWS - Micronaut

This project is part of a comparative test between **Micronaut** and **Spring Boot** to evaluate:

- **Startup Time**: Measure the time required for the application to be ready to process requests.
- **Response Time**: Assess the latency of requests in an AWS Lambda environment.
- **Code Complexity**: Compare the simplicity and clarity of the code between the two frameworks.

## Project Description

This repository contains an implementation of an AWS Lambda function using the **Micronaut** framework. The application is configured to run as a Lambda function and uses Micronaut's `lambda` runtime.

### Key Technologies Used

- **Java 21**
- **Micronaut 4.7.6**
- **AWS Lambda**
- **Maven**

## Project Structure

- **`src/main/java/dev/tailf/Application.java`**: Main class that initializes the Micronaut application.
- **`pom.xml`**: Maven configuration, including dependencies and plugins required for Micronaut and AWS Lambda.
- **`mvnw`**: Maven wrapper to simplify command execution.

## Setup and Execution

### Prerequisites

- **Java 21** installed.
- **Maven** or the `mvnw` wrapper included in the project.
- An AWS account configured with permissions to create and run Lambda functions.

### Steps to Execute

1. **Build the project**:
   ```bash
   ./mvnw clean package

## Dependencies documentation

### Handler

Handler: io.micronaut.function.aws.proxy.payload1.ApiGatewayProxyRequestEventFunction

[AWS Lambda Handler](https://docs.aws.amazon.com/lambda/latest/dg/java-handler.html)

- [Micronaut Maven Plugin documentation](https://micronaut-projects.github.io/micronaut-maven-plugin/latest/)

### Feature aws-lambda documentation

- [Micronaut AWS Lambda Function documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/index.html#lambda)

### Feature snapstart documentation

- [https://docs.aws.amazon.com/lambda/latest/dg/snapstart.html](https://docs.aws.amazon.com/lambda/latest/dg/snapstart.html)

### Feature micronaut-aot documentation

- [Micronaut AOT documentation](https://micronaut-projects.github.io/micronaut-aot/latest/guide/)

### Feature maven-enforcer-plugin documentation

- [https://maven.apache.org/enforcer/maven-enforcer-plugin/](https://maven.apache.org/enforcer/maven-enforcer-plugin/)

### Feature aws-lambda-events-serde documentation

- [Micronaut AWS Lambda Events Serde documentation](https://micronaut-projects.github.io/micronaut-aws/snapshot/guide/#eventsLambdaSerde)

- [https://github.com/aws/aws-lambda-java-libs/tree/main/aws-lambda-java-events](https://github.com/aws/aws-lambda-java-libs/tree/main/aws-lambda-java-events)

### Feature serialization-jsonp documentation

- [Micronaut Serialization JSON-B and JSON-P documentation](https://micronaut-projects.github.io/micronaut-serialization/latest/guide/)



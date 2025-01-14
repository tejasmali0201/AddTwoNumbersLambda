# AddTwoNumbersLambda

#Overview
This project is an AWS Lambda function written in Java to add two numbers and return the result. The function follows the standard AWS Lambda structure and can handle input validation and error reporting. The project is built using Maven for dependency management and ease of deployment.

#Features
Add Two Numbers: The Lambda function takes two numbers as input and returns their sum.
Error Handling: Handles missing or invalid inputs gracefully.
Java-Based: Uses Java 11+ for implementation.
AWS Lambda Ready: Easily deployable on AWS Lambda with necessary configurations.

#How to Run
Install Required Tools:

Ensure you have Java 11+, Maven, and AWS CLI installed.
Configure AWS CLI with your credentials.
Clone or Create the Project:

Use the directory structure and dependencies mentioned in the README to create the project.
Write the Lambda Function:

Add the AddTwoNumbersLambda.java file under the package com.example.
Build the Project:

Run mvn clean install in the terminal. This creates a deployable JAR file in the target/ directory.
Deploy to AWS Lambda:

Use the AWS CLI command to create the Lambda function and deploy the JAR file.
Test the Function:

Use the AWS Lambda Console or AWS CLI to provide JSON input and test the function.

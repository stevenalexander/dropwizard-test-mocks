# Dropwizard test mocks

Simple Dropwizard example showing how to test with mocks, forked from [Dropwizard-login](https://github.com/stevenalexander/dropwizard-login).

## Requirements

* Java 1.7
* Maven

## Setup

To build:
    ```
    mvn package
    ```

To test:
    ```
    mvn test

To run jar:
    ```
    java -jar target/login-0.0.1-SNAPSHOT.jar server login-service.yml
    ```

1. Point DB config at database matching the schema sql in db\schema.sql

2. Create the [yaml configuration file](http://dropwizard.codahale.com/manual/jdbi/) containing the DB config, login-service.yml

3. Post to http://localhost:8080/session with valid values for fields 'username' and 'password' to try out.

## Mocks

TODO


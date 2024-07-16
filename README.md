# BibliotecaAlura

BibliotecaAlura is a web application designed for book management. Built with Spring Boot and PostgreSQL, it provides an intuitive interface to manage books.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)


## Requirements

Before starting, ensure you have installed:

- [Java 11+](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Maven 3.6+](https://maven.apache.org/download.cgi)
- [PostgreSQL](https://www.postgresql.org/download/)

## Installation

To install and run BibliotecaAlura on your local machine, follow these steps:

1. **Clone the repository**

   ```sh
   git clone https://github.com/aaronbarra040998/Oracle_challenge_bibliotecalura.git
   cd Oracle_challenge_bibliotecalura

2. **Compile and package the project with Maven**

   ```sh
   mvn clean package
   ```

## Configuration

1. **Edit the Spring Boot properties file**

   Open `src/main/resources/application.properties` and adjust the database configuration according to your environment:

   ```properties
   spring.application.name=BibliotecaAlura

   spring.datasource.url=jdbc:postgresql://localhost:5432/liter_alura
   spring.datasource.username=postgres
   spring.datasource.password=your_password
   spring.datasource.driver-class-name=org.postgresql.Driver
   spring.jpa.database-platform=org.hibernate.dialect.PostgreSQLDialect

   spring.jpa.hibernate.ddl-auto=update

   spring.jpa.show-sql=true
   spring.jpa.format-sql=true
   ```

## Usage

To run the application, click on the green button in the `LiteraluraApplication` file in IntelliJ IDEA.

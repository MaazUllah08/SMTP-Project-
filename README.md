# SMTP Email Service

A simple **Spring Boot SMTP project** for sending emails using `JavaMailSender`. It demonstrates basic email functionality with a clean and easy-to-understand implementation.

## Features

* Send plain-text emails
* Send HTML emails
* Support CC and BCC
* SMTP configuration
* Basic exception handling

## Tech Stack

* Java 17+
* Spring Boot
* Spring Mail / JavaMailSender
* Maven

## Configuration

Add your SMTP details in `application.properties`:

```properties
spring.mail.host=smtp.example.com
spring.mail.port=587
spring.mail.username=your-email@example.com
spring.mail.password=your-password
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true
```

**Note:** Keep your SMTP credentials secure and never commit them to GitHub.

## Run the Project

```bash
mvn clean install
mvn spring-boot:run
```

## Use Cases

Useful for implementing **OTP, verification, password reset, notification, and transactional emails** in Spring Boot applications.

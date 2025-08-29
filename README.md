# Bajaj Finserv Health | Qualifier 1 | JAVA

## Overview

This Spring Boot application automates the Bajaj Finserv Health Qualifier workflow:

- On startup, it sends a POST request to the BFHL API to generate a webhook and access token.
- Based on your registration number, it selects and submits the correct SQL query to the webhook using the received token.
- All logic is triggered automatically (no REST endpoints required).

## Build & Run Locally

### 1. Clean, build, and generate JAR

```
mvn clean package
```

The JAR will be generated in the `target/` folder.

### 2. Copy JAR to release folder

```
powershell -Command "Copy-Item -Path target/*.jar -Destination release/app.jar"
```

### 3. Run the JAR

```
java -jar release/app.jar
```

## GitHub & JAR Download

- [GitHub Repository](https://github.com/hemabhi26/springboot-sql-webhook) <!-- Replace with your actual repo URL -->
- [Download Raw JAR](https://github.com/hemabhi26/springboot-sql-webhook/blob/main/release/app.jar) <!-- Replace with actual JAR link -->

## Git Commands

### Initialize Git & Push to GitHub

```
git init
git checkout -b main
git remote add origin https://github.com/your-username/your-repo.git # Replace with your actual repo URL
git add .
git commit -m "Initial commit: Bajaj Finserv Health Qualifier 1 JAVA"
git push -u origin main
```
h -u origin mainecho \#\ springboot-sql-webhook
# springboot-sql-webhook

# Selenium Automation Framework Saucedemo
 
## Prerequisites

- [JDK 11](https://www.oracle.com/co/java/technologies/javase/jdk11-archive-downloads.html) (Environment variable)
- [Maven](https://maven.apache.org/download.cgi) (Environment variable)
- [Allure](https://docs.qameta.io/allure-report/#_installing_a_commandline) (Environment variable)
- IDE (ex. [IntelliJ](https://www.jetbrains.com/idea/download/#section=windows))

## Run project

```bash
mvn clean verify
```

## Open allure report

```bash
allure serve target/allure-results
```

# Rest API

Rest API is a Spring Boot Project designed to help you get to grips with the Spring Boot Framework

## Installation

* [Fork the repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)

* Clone your own repo on your local machine

* Add the upstream pointing to the original repo (the one who has been fork) 

## Usage

* Build the project

```bash
   mvn dependency:resolve
```

* Launch the application

```bash
    mvn spring-boot:start
```

* Test a first api call

```bash
    curl curl http://localhost:8080/greeting?name=Use
```

## Licence

The repo is based on official sample provided by [the Spring community](https://spring.io/guides#gettingStarted)
# Authentication API

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Mysql](https://img.shields.io/badge/mysql-4479A1?style=flat&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

This project is an API built using **Java, Java Spring, Flyway Migrations, PostgresSQL as the database, and Spring Security and JWT for authentication control.**

The API was developed for my School Idividual Project where i created a School Managment System for low Condition schools

## Table of Contents

- [Installation](#installation)
- [Configuration](#configuration)
- [Wireframes](https://www.figma.com/file/KvaGj9zC3bPkSHppJ09kBj/Gustavo-Educaplus?type=design&node-id=0%3A1&mode=design&t=EMhg6O3I7BLUzfDQ-1)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Authentication](#authentication)
- [Dependecies](#)
- [Database](#database)
- [Contributing](#contributing)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Gustavolskw/EducaPlus.git
```

2. Install dependencies with Maven

3. Install [MySql](https://dev.mysql.com/downloads/installer/)

## Usage

1. Start the application with Maven
2. The API will be accessible at http://localhost:8080


## API Endpoints
The API provides the following endpoints:

```markdown

POST /auth/login - Login into the App

POST /auth/register - Register a new user into the App
```

## Authentication
The API uses Spring Security for authentication control. The following roles are available:

```
USER -> User - Alunos
ADMIN -> Admin - Professores e Gestores
```
To access protected endpoints as an ADMIN user, provide the appropriate authentication credentials in the request header.

## Database
Dependecies Used for backend of my project were: 
```
#spring-boot-starter-data-jpa
#spring-boot-starter-security
#spring-boot-starter-validation
#spring-boot-starter-web
#spring-boot-devtools
#mysql-connector-j
#lombok
#spring-boot-starter-test
#spring-security-test
#java-jwt
#flyway-core
		
```
##API Documentation 
run api and search for those URLs
```markdown

GET http://localhost:8080/swagger-ui/index.html - Swagger Ui to see endpoints and data
GET http://localhost:8080/v3/api-docs - Swaager Json Format for endpoints and data
```


## Database
The project utilizes [Mysql](https://www.mysql.com/) as the database. The necessary database migrations are managed using Flyway.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request to the repository.

When contributing to this project, please follow the existing code style, [commit conventions](https://www.conventionalcommits.org/en/v1.0.0/), and submit your changes in a separate branch.





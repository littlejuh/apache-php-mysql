# Apache + PHP + MySQL + phpMyAdmin
Docker running Apache, PHP, Composer, MySQL and PHPMyAdmin.

## Install prerequisites
This project has been mainly created for Unix (Linux/MacOS). Perhaps it could work on Windows.

 - [Docker](https://www.docker.com/)
 - [Docker Compose](https://docs.docker.com/compose/install/)

## Run the project
    make run

## Exposed services 
This project expose the following ports :
| Server | Port  |
|--|--|
| Apache | 8080 |
| PHPMyAdmin | 8282 |


## Stop project

    make down

# School API
> Status: Complete ✅ <br>
This repository contains a basic School CRUD API built in NodeJs to test my skills around SQL, Google Cloud Platform and Docker.

## Dependencies:
* ExpressJS
* MariaDB
* Sequelize
* DotEnv
* BcryptJs
* Json Web Token
* Multer

## CRUD Models
* Users - Required registration to allow student registration
* Alunos - Student registration
* Photo - Images that can be related with "Alunos" model with the ID

## Requirements
* .env file configuration
* Node_modules installed
* An available SQL Database (MariaDB)

### .env File config
DATABASE= __databaseName__ <br>
DATABASE_HOST=__databaseIpAdress__ <br>
DATABASE_PORT=__databasePORT__ <br>
DATABASE_USERNAME=__databaseUserName__ <br>
DATABASE_PASSWORD=__databasePassword__ <br>

TOKEN_SECRET=__databaseSecretToken__ <br>
TOKEN_EXPIRATION=7d __expirationRange__ <br>



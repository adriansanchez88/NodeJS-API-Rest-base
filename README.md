# API Rest base
>This is the repository used during the development of the **'API Rest base'**.

## Table of Contents
- [Description](#description)
- [Development](#development)
- [How to use](#how-to-use)
- [Author Info](#author-info)

## DESCRIPTION
**'API Rest base'** is a base api to start new projects.

[Back To The Top](#api-rest-base)

## DEVELOPMENT
All files in this repository were developed using *Node.js v14.15.5*, and the following dependencies are needed to run the project:

    - dotenv (v8.2.0): A zero-dependency module that loads environment variables from a .env file into process.env. Storing configuration in the environment separate from code is based on The Twelve-Factor App methodology.
    - express (v4.17.1): Used to provide server-side logic for web and mobile applications.
    - morgan (v1.10.0): HTTP request logger middleware for node.js.
    - swagger-ui-express: (v4.1.6): This module allows you to serve auto-generated swagger-ui generated API docs from express, based on a swagger.json file.
    - winston: (v3.3.3): Designed to be a simple and universal logging library with support for multiple transports.

[Back To The Top](#api-rest-base)

## HOW TO USE
It brings as an example the *User* model with two fields (*id* and *name*).

It consists of the following *services*:

- **getAllUsers**: Get a list of all existing users. *(GET/users/)*
- **createUser**: Create a new user. *(POST/users/)*
- **updateUser**: Update an existing user by providing the id. *(PUT/users/{id})*
- **deleteUser**: Delete an existing user by providing the id. *(DELETE/users/{id})*

Check *documentation* of the API to see how it works.

[Back To The Top](#api-rest-base)
## AUTHOR INFO
- **Email**: adriansanchez88@gmail.com

- **LinkedIn**: [adrián-sánchez-nievares-50a310159](https://www.linkedin.com/in/adri%C3%A1n-s%C3%A1nchez-nievares-50a310159/)

[Back To The Top](#api-rest-base)
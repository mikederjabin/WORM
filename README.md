# Project WORM

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](#license)


## Table of Contents
* [Technologies Used](#tech)
* [Description](#description)
* [User Story](#UserStory)
* [Installation](#installation)
* [License](#license)
* [Credits](#Credits)

## Description

WORM is an bookshelf application that allows users to search for books by entering a specific query (Title, Author, Exerpt, etc). The user then submits the query, which calls upon the Google Books API that will return an array of books with the corresponding data of the book that was searched for (Title, Author, Published Date, etc.) The user will be able to see the list of books that relate to the search populate on the page. Users can then save their favorite books to their own personal bookshelf library, and share share that bookshelf with other users via email.

![SampleBookShelf](SampleBookShelf.png)

## User Story

The client is represented as a user who likes to read and likes to keep track of their favorite books. The client can use WORM's book search to find books they would like to read or keep track of.

Books that meet the user's search criteria will be displayed upon search.

Users can add books to their personal bookshelf library, which will be displayed in a separate page of the navigation bar. 

## Installation

To use properly you need to install Node.js and in the terminal you have to use the command 
``` npm init -y ```
and then also install the following dependencies 
``` npm install express ```  to install express
``` npm install express-handlebars  ``` to install handlebars
``` npm install mysql ``` to install mysql
``` npm install dotenv ``` for the environment variable 
``` npm install passport ``` for authentication
``` npm install bcryptjs ```  for authentication / password hashing
``` npm install sequelize ``` for the  sequelize databases


## Tech

* HTML
* CSS
* Handlebars
* NodeJS
* Express 
* MySQL 
* Sequelize
* Passport
* Bootstrap
* JQuery
* Heroku
* Jaws_DB addon for Heroku
* [Google Books API](https://developers.google.com/books)
* [NodeMailer](https://nodemailer.com/usage/)

## Credits

WORM was created by team members from UC Davis's Part-Time Full Stack Coding Bootcamp: 

* [Pirooz Wallace](https://github.com/attack-theoRy)
* [Mike Derjabin](https://github.com/mikederjabin)
* [Alex Bachicha](https://github.com/alexbachicha)
* [Eli Derjabin](https://github.com/derjabineli)

## License 

Licensed under the [MIT License](LICENSE.txt)
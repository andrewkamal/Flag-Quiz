# Flag Quiz

## Description

This is a simple flag quiz game built with JavaScript, Node.js, and EJS. The game presents a flag to the user and they have to guess the country that the flag belongs to.

To play the game, it is preferable to use firefox as the browser for the flags to be displayed properly.

Also, it is important to add the content of the flag.csv into a database and a table to be able to play the game.

## Installation

1. Clone the repository:
```sh
git clone 
```
2. Navigate to the project directory:
```sh
cd Flag-Quiz
```
3. Install the required dependencies:
```sh
npm i
```
4. Update the content of the the DB connection string in the index.js file to match your database connection string.
```sh
user: "postgres",
host: "localhost",
database: "world",
password: "123456.",
port: 5432,
```
## Usage

To start the game, run the following command in your terminal:
```sh
nodemon index.js
```
Then, open your browser and navigate to http://localhost:3000 to start playing the game.
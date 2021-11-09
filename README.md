
## Description

This app allows a user to create and delete, and view previously saved notes. The app uses an Express backend to save and retrive note data from a JSON file. The back end contains the following routes:

### HTML Routes

* GET /notes - Returns the notes.html file.
* GET * - Returns the index.html file

### API Routes

* GET /api/notes - Reads the db.json file and returns all saved notes as JSON.
* POST /api/notes - Receives a new note to save on the request body, adds it to the db.json file, returns the new note to the client.
* DELETE /api/notes/:id - Receives a query parameter containing the id of a note to delete, removes the note with the given id property, and then rewrites the notes to the db.json file.

### User Story

AS A user, I want to be able to write and save notes

I WANT to be able to delete notes I've written before

SO THAT I can organize my thoughts and keep track of things I need to complete

## Table of Contents

* [Description](#description)
* [Deployed Link](#deployed-link)
* [Technologies](#technologies)
* [Installation](#installation)
* [Usage](#usage)


## Deployed Link

Deployed on Heroku at:  [The Note Taker](https://the-note-taker21.herokuapp.com/)



## Technologies

* [Node.js](https://nodejs.org/)
* [Express](https://expressjs.com/)
* [Heroku](https://heroku.com)

## Installation

To install dependencies, run the following:

`
npm i
`

## Usage

After downloading the files and installing dependencies, run 

`
node server.js
`

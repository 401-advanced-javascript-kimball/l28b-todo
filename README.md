# l28b-todo

# LAB - 28b - To Do

## Project Name

### Author: Student/Group Name

### Links and Resources
* [submission PR](https://github.com/401-advanced-javascript-kimball/l28b-todo/pull/1)
* [travis](https://travis-ci.com/401-advanced-javascript-kimball/l28b-todo)
* [front-end](http://xyz.com) (when applicable)

#### Documentation
* [jsdoc](http://xyz.com) (Server assignments)
* [styleguide](http://xyz.com) (React assignments)

### Modules
#### `modulename.js`
##### Exported Values and Methods

###### `foo(thing) -> string`
Usage Notes or examples

###### `bar(array) -> array`
Usage Notes or examples

### Setup
#### `.env` requirements
* `PORT` - Port Number
* `MONGODB_URI` - URL to the running mongo instance/db

#### Running the app
* `npm start`
* Endpoint: `/foo/bar/`
  * Returns a JSON object with abc in it.
* Endpoint: `/bing/zing/`
  * Returns a JSON object with xyz in it.
  
#### Tests
* How do you run tests?
* What assertions were made?
* What assertions need to be / should be made?

#### UML
Link to an image of the UML for your application and response to events

----------

# LAB - Props and State

This lab is an opportunity to practice passing props and state between components. Its also the first refactoring of a "To Do List" application.

## Before you begin
Refer to *Getting Started*  in the [lab submission instructions](../../../reference/submission-instructions/labs/README.md) for complete setup, configuration, deployment, and submission instructions.
## Getting Started

Starter code has been provided for you in the `/lab/starter-code` folder. 

Open [Code Sandbox](http://codesandbox.io) and Create a new application. When prompted, choose "From GitHub" and then paste in the URL to the correct starter code folder from your fork of the class repository.

You will be submitting the URL to this working sandbox as part of your assignment.

---

## To Do Application Refactor

Begin with: `/lab/starter-code/todo`

You will be refactoring this simple "To Do" application, written with HTML, CSS, Vanilla Javascript and Handlebars Templates in a React app.

* Create a new React application at [Code Sandbox](http://codesandbox.io)
* Replicate the functionality of the starter application
  * Add whatever is typed into the form to the list
  * Clicking an item changes it's 'complete' state
    * Use that to set a new class on the item for styling
  * Clicking the delete link removes the item from the list
* Some basic CSS has been provided in the starter code
  * Convert this to SASS

### Recommended Steps

* Ignore Events because React will cover that
* Properties that are being changed are they worth being put in state
* What is each function doing
* Index and Todo combined in React Component
  * There is a template in the todo.js
    * It has a header and list in it
* Item is a constructor
  * Creating data so should it be it’s own class
* You may want to have a parent app with a child todo  

## Tests

Write mount/enzyme tests for each component in all assignments

## Assignment Submission Instructions
Refer to the the [lab submission instructions](../../../reference/submission-instructions/labs/README.md) for the complete lab submission process and expectations

----------


---
title: JS Fun at the Library
---

## Overview

In front end web development, the programming language you will encounter most
often is JavaScript. Soon, we'll also use HTML and CSS to help a user interact
with our applications, however before we do that, we need to understand how to
use JavaScript to handle the logic of our applications.

In this project, you'll be gaining experience working with variables, primitive
data types, looping, arrays, objects and classes. As you work through the
iterations, be sure to take time to stop and refactor you solutions. There is
rarely one right way to solve a problem in programming, and part of your job
will be evaluating the trade offs between different approaches to solving a
problem.

## Learning goals

  - Understand JavaScript data types and how/when to use them
  - Understand how to declare variables and assign data to them
  - Practice using objects and arrays, including `for loops`
  - Write functions that require conditional logic, parameters/arguments, and `return`
  - Read and understand unit tests, and pass them

## Setup

  - Fork [this project](https://github.com/solidkraft/js_library){:target="_blank"} to your own Github account
  - clone the repository to your local machine
  - `cd` into the project
  - run `npm install` to install the necessary dependencies

## Iterations

### 0: Practice Variables, Primitives, Functions, Arrays, and Objects

  - In the `src/` directory, you'll find a file called 'warm-up.js'. Read
    through the instructions in the file carefully. The exercises in this file
    will help you to complete the rest of the iterations  

### 1: Complete the book tests

  - For the rest of the iterations, you will be working to build out some
    js functionality, using a test suite as your guide.  
  - Start with the `book.js` file.  
    - Unskip the first test in `test/book-test.js`  
    - Run `npm test test/book-test.js`  
    - Read the error messages CAREFULLY!  
    - Make the test pass.
  - Ensure that all of the skips are removed from the test file when you push up to GitHub.
  - Before moving on to the next iteration, take time to refactor your
    solutions. Is this the best approach to solving the problem? Is there a
    different way you could make the tests pass? 

### 2: Complete the shelf tests

  - Unskip the first test in `test/shelf-test.js`, and get to work passing the tests
  - Run `npm test test/shelf-test.js`  
  - Ensure that all of the skips are removed from the test file when you push up to GitHub.
  - Before moving on to the next iteration, take time to refactor your
    solutions. Is this the best approach to solving the problem? Is there a
    different way you could make the tests pass?  

### 3: Complete the library tests

  - Unskip the first test in `test/library-test.js`, and get to work passing the tests
  - Run `npm test test/library-test.js`  
  - Ensure that all of the skips are removed from the test file when you push up to GitHub.
  - Before moving on to the next iteration, take time to refactor your
    solutions. Is this the best approach to solving the problem? Is there a
    different way you could make the tests pass? 

### Extension: Refactoring
  - Revisit your `addBook` and `checkoutBook` functions.  Consider any similar lines of code and how you might refactor both functions to make use of bracket notation. 
  - Refactor `takeStock` so that it dynamically checks to see if the book exists in the correct shelf.  Note you will need to make use of bracket notation in this solution as well.  
  - Ensure that all tests still pass after refactors have been made.

## Self-Assessment

The goal of this project is not completion. The goal is to put into practice some of the tools we've been discussing (pseudocoding, rubber ducking, problem solving), and to practice writing fundamental JavaScript.

The value of this project, and every project, lies in the learning that you do and the growth that you demonstrate over the course of it. We expect you to work hard for the benefit of your own learning.

The skills you will develop over the course of this project are:

- Understanding fundamental JS:
    - functions
    - manipulating arrays
    - manipulating objects
    - testing
- Problem solving:
    - Pseudocoding
    - Articulating code (while reviewing, or rubber-ducking)
- Time management
- Git workflow

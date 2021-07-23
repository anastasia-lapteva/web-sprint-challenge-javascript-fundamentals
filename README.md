# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

".map" is used for converting data. ".map" returns a new array.
For example, you could have an array of objects (person). Each object (person) could have a first name, last name, and number of pets. You could use ".map" to create a new array with just first names taken.

".reduce" returns a single value. ".reduce" is used for addition (sums) and multiplication (products).
Continuing the same example, let's say you want a single number of all the persons' number of pets. You could use ".reduce" to reduce all number of pets data down to a single value.

".filter" returns a new array based on if something (specified by the programmer) is true (included) or false (excluded).
Continuing the same example, let's say you want to filter out all persons with the last name "Smith". You could use ".filter" to go through all items in the array and return only what we want: persons with last name "Smith".

2. Explain the difference between a callback and a higher order function.

A higher order function is a function that takes another function (callback) as an argument.

A callback function is a function that is passed  to another function (higher order) with the expectation that the other function (higher order) will call it.

3. Explain what a closure is.
    Closure means that an inner (nested) function always has access to the variables and parameters of its outer function (that it is nested inside of).

4. Describe the four principles of the 'this' keyword.

  (1.) Window/ Global Object Binding
  When in strict mode, 'this' will return undefined.
  When not in strict mode, 'this' will return the window in node.
  If we get either of these answers, it means we have not given 'this' any context so it is defaulting to the main window/ global object we are working inside of.
  Window binding is an error, we do not want it to happen.

  (2.) Implicit Binding
  When the function is invoked, whatever is to the left of the dot (leftOfTheDot.this) is what is being referenced by 'this'.

  (3.) New Binding
  When a function is invoked as a constructor function using the 'new' keyword, 'this' will point to the new object that is created.
  Building a constructor function is like building a template for new objects.
  When we invoke the constructor function, the invocation builds a new object.
  The 'this' keyword points to the new object that is created.

  (4.) Explicit Binding
  We explicitly assign the 'this' keyword using '.call', '.apply', or '.bind' methods.

5. Why do we need super() in an extended class?

"super()" is used to access and call functions on an object's parent.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)


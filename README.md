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
    a).map() returns a new array of elements where you use a function to change the original element's value inside of it. It's used for reshaping or manipulating data. For an example, you have a data set of all the NFL super bowl games, winners, scores, teams, etc. If you want to be find the teams who played at the Super Bowl from the past to the current, you would use .map() to map through the data looking for only the teams' names and the years. 
    b) .filter() returns a new array of elements where it is a 'truth' test, filtering specific conditions of that array. From the example above, you want to find the winners from those years, you would filter from that using .filter() with an if statement that if team 1 final score > team 2 final score, return the name of the team else, return name of team 2.
    c) .reduce() returns a new array of elements where you want to add them all up from the first element to the last. Taken from the example from above, you want to find the average scores of all superbowl games, you would use .reduce(), which it will add all the final scores and divide it by the total amount of games played.

2. Explain the difference between a callback and a higher order function.
    A callback is a function passed as an argument to another function where it allows that function to call another function. Higher Order Function (HOF) are functions that operate on other functions either as parameters or returning them. 

3. Explain what a closure is.
    Closure is a combination of a function and the lexical environment within which that function was declared. When a function is declared and created, a new scope is created called a functional scope. The variables or functions declared within that function have the ability to reach outward for context but never inward. This will remain true no matter how deep you nest functions.

4. Describe the four principles of the 'this' keyword.
    a) Window/Global binding: when in the global scope, the value of 'this' will be in the console object. It will display everything in the global scope.
    b) Implict binding: whenever a poceeding dot calls a function, the object before the dot (to the left) is 'this'. 
    c) New binding: whenever we use a constructor function, 'this' refers to the specific instance of the object that is created and returned by the constructor function.
    d) Explicit binding: whenver we use a .call(), .applly(), or .bind() method, 'this' is explicitly defined.

5. Why do we need super() in an extended class?
    We need super() in an extended class because 

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


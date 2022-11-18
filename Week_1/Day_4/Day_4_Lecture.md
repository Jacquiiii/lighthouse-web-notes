## Day 4 Lecture Notes: Nov 17, 2022

* Function reusability can be achieved by using parameters
    * More reusability can be achieved if one of the parameters is a function that does an action
* High order functions:
    * Needs another function to work (callback). Callback is a relationship between a high order function and a function.
    * Callback func is called in the console.log() statement or equivalent by referencing it’s name as the argument, don’t need to call the function but rather just put the name
* forEach():
    * Loops through array and performs a function on each item.
    * Get access to it’s element, index and entire array (in function use those or as many of those as you want to use)
* .map
    * Takes an array and produces a new array with changed content
    * Can store as a var to return it
* Arrow functions
    * More concise
    * Use when it makes sense
    * Can use implicit return with no {} for simple things
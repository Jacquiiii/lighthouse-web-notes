## Day 4 Lecture Notes: Nov 17, 2022

* Play the what is this game
    * Assignment operator is the equal sign
    * Follow up question is what is next
* module.exports makes the code exportable
    * You can assign a function to it using the assignment operator
    * Example: module.exports = sayHello;
    * If you have multiple functions to export, put them in an object
* Import the file by going to the file where you want to input it to, and the use the require function
    * ./ = look for the file in the local directory
    * ../ means go up one directory
* To change a variable name, right click and change variable, then it will change all variables
* Assertions:
    * Assert is a function object we can use to do testing
    * const assert = require(‘assert’);
    * assert.equal(return value, actual value);
* Npm:
    * For managing a package of software
    * node_modules/ is all packages needed in order to use the package you are trying to install
    * npm init turns into a package
    * npm install will install all dependencies and create a package-lock json file
    * 
* Mocha:
    * Mocha is a framework not a library
        * The framework calls the functions
    * it function
        * Takes two params: label to describe the test, and a callback function passed as a function literal (gets executed when mocha calls the test)
        * Make sure to treat tests like an object if there was more than one function exported and can call each function with the dot notation
    * describe function
        * Used to execute more than one test
        * Written the same as the it function but you move all your its to the function callback body
    * .node_modules/.bin/mocha runs the test but you can update the json file with this so we can update
* Chai:
    * Is an npm package
    * Assertion library
* TDD
    * Test. Driven. Development
    * Writing tests before executing code

### Links

* [Code demo & notes](https://github.com/ChristianNally/web-2022-Nov-14-Telus)
* [Lecture recording](https://vimeo.com/773558706/ec2fdf85bb)
# Node Testing

Test-driven development (TDD) is an approach to the software development process. As the name implies, it involves utilizing tests to guide application development. 

In order to learn TDD and practice unit testing in Node.js, it will be helpful to familiarize ourselves with various testing libraries and frameworks. In this unit, we'll be using [Jest](https://jestjs.io/docs/getting-started), an open-source JavaScript testing framework.  

## Exercises

**Level 1**

- Create a file that stores various math operations: sum, substraction, multiplication, and division. Write a test and run it to ensure the program is working correctly. 

- Go back to 1.3 ('Promises and Callbacks'), Level 1, exercise 2. Write and run tests for the two functions.

- Go back to 1.3 ('Promises and Callbacks'), Level 2 exercises 1&2. Write and run tests for the functions getEmployee() & getSalary().

- Go back to 1.4 ('Async/Await'). Write and run tests for the code in Level 1, exercise 2. 

**Level 2**

- Go back to 1.4 ('Async/Await'). Use tests to verify the  code for Level 2, exercise 1 works.

- Go back to 1.2 ('Classes & Arrow Functions), Level 2, exercise 2. Create a mock to test the class Person and verify calls its constructor and sayName() method work;

- Go back to 1.2 ('Classes & Arrow Functions), Level 3, exercise 1. Use tests to verify class instantiation works.

## Instructions

In order to conduct the testing, I've written the code to be tested in its own .js file with a separate, matching .test.js file. I've created two folders, **src** -- where .js files to be tested are stored -- and **__tests__** -- where test cases for unit testing are stored. 

To execute the code, please do:

1 - Install dependencies:

`````
npm install
`````

2 - Run tests:

`````
npm test
``````

    

## 102 - Day 07

## What I learned today

### Intro + Scripts

- javascript can make a web page feel interactive by responding to what the user does

- Access Content:
    - can select an element and place 
    - can retrieve data from an element

- Modify Content:
    - replace text within the element
    - change the position or size of an image

- Program Rules:
    - Can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page
    - Gallery script could check which image a user clicked on and then display a large version of that image
    - A mortgage calculator could collect values from a form, perform a calculation, and display repayment

- Reaction to events:
    - You can specify that a script should run when a specific event has occurred.
    - a button is pressed
    - when a link is clicked
    - information is added or not added in a form
    - an interval of time has passed

- a script is a series of instructions that a computer can follow to achieve a goal.
- scripts are made up of instructions a computer can follow step-by-step
- scripts can run different sections of the code in response to the situation around them
- a programmer must give the computer enough detail to perform the task as if every time were its first time
  
1. Define the goal
    - think of a puzzle or problem for the computer to solve
2. Design the script
    - split the goal into a series of tasks
    - like writing a recipe that it can follow
3. Code each step
    - each of the steps needs to be written in a programming language that the computer understands

- As tempting as it can be to start coding straight away, it pays to spend some time designing your script before you start typing it
    - Flowchart it (reference page 23)

- computers solve things programmatically


### Expressions + Operators
- AND = &&
- OR = ||
- Arithmetic: basic math
- String concatation: adding 1 or more strings together to form 1 string


### Functions

- Proper ways to write functions:

    - ```var someName = function(parameter) {
        console.log('a new world awaits');
    }```
    - ```function helloWorld(name) {
        console.log('a new world awaits');
    }```

- Functions let us define code ONCE, and then run the code whenever we need it.
- Well named functions communicates clearly it's purpose
- DRY (Do not Repeat Yourself)
- Functions make code reusable
- A reusable set of step-by-step instructions, portentially based on input, to potentially provide some output
- 2 parts of a function: 
    - Declaring:
    - Invoking:

- functions are invoked by using parenthesis


### Lecture notess
```
var num = 10;
var str = 'some words';
var tru = true;
var fls = false;

// console logs are simply for developers
console.log('sum', 10 + 10);

// concatendated string
console.log('sum: ', 10 + '10');

// falsey + truthy (not really data types)
var person;
console.log(person) // undefined

if (person) { console.log('you can see me')};


//function declaration
// 'a' and 'b' are parameters
// output of this function is a 'console.log()' of the sum
// functions are good at I/O
function add(a, b) { //input
    // console.log('value of a: ', a);
    // console.log('value of b', b);
    // console.log('sum: ', a + b); //output
    return a + b;
}

//function invocation (aka calling function)
add(10, 5) // arguments
add(89, 129019);

// our function returns a number, so we can use it for math
// functions meanst to encapsulate information
add(10, 5) * add(19, 20) + add(10, 500)

// DRY coding paradigm (do not repeat yourself)
```


### Tips
- `parseInt()`

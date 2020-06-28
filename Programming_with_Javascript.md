-[Return to Home](/README.md)

# Learning Journal
*Blog Entry-* Lab 07

## Programming with Javascript
Javascript allows developers to access items within their code, modify these items, create a series of steps for the browser to follow, and tell the code how to react to certain events.

In short, it has the ability to:
- Access
- Modify
- Program
- React

This makes for a more interactive webpage!

### Script
But how does it do this?  At its most basic level, JavaScript is a set of instructions that give exact details about what to do next.  This is called a **script**.  Think of it like a recipe in a cookbook.  The recipe tells you exactly what ingredients to use, how much to use, when to use them, and what to do to make the final dish.

#### Writing a Script
Before starting to code, writing it all down in a script helps you cover all our bases. Set your *goal* first. Then, *design a flowchart* showing exactly what you need to do (**tasks**).  Once you have your tasks laid out, they write the **steps** that must take place for the tasks to run. 

Finally, you can *code* your JavaScript.

### Operators
Operators in JavaScript allow developers to add more than one value together to make a single value.

- **Assignment:** There is only one assignment operator, the equal sign (=). It 'assigns' value to the variable.
- **Arithmetic:**  These operators perform basic math.
    - addition: +
    - subtraction: -
    - division: /
    - multiplication: x
    - increment: ++ (adds one)
    - decrement: -- (subtracts one)
    - modulus: % (returns the remainder after dividing two numbers)
- **String:**  There is only one string operator, the plus sign (+). It combines strings together.

### Functions
A function in JavaScript performs a single task.  It can include one or more statements.  For instance, the following code is a function whose sole purpose is to write the word "Hello!"

function sayHello() {
    document.write('Hello!');
}

They sometimes need information to run.  This information goes within the (currently) empty parenthesis on the first line.

Functions can return one or more values.  However, the function above returns only one.
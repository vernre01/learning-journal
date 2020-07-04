-[Return to Home](/README.md)

# Learning Journal
*Blog Entry-* Lab 08

## Operators and Loops

### Operators
JavaScript allows coders to use symbols to compare values (creates a single expression) and compare the comparison of values (compares two or more expressions).  

Symbols that compare values are called Comparison Operators:

- **==** : EQUAL TO - Compares two values to determine if they are equal.
- **!=** : NOT EQUAL TO - Compares two values to determine if they are not equal.
- **===** : STRICT EQUAL TO - Compares two values AND their data type to determine if they are equal.
- **!==** : STRICT NOT EQUAL TO - Compares two values AND their data type to determine if they are not equal.
- **>** : GREATER THAN - Compares two values to determine if the first value is greater than the second.
- **<** : LESS THAN - Compares two values to determine if the first value is less than the second.
- **>=** : GREATER THAN OR EQUAL TO - Compares two values to determine if the first value is greater than or equla to the second.
- **<=** : LESS THAN OR EQUAL TO - Compares two values to determine if the first value is less than or equal to the second.

Symbols that compare expressions are called Logical operators:

- **&&** : AND - If both expressions are *true*, it returns *true*.
- **||** : OR - If at least one expression is *true*, it returns *true*.
- **!** : NOT - If the statement is *false*, it returns *true*. If the statement is *true*, it returns *false*.

### Loops
Instead of copying and pasting code over and over that should run multiple times, developers can use **Loops**.  The three Loop types are **FOR**, **WHILE**, and **DO WHILE**.

#### FOR
Used when you know exaclty how many times you want the code to run, a **FOR** Loop usually uses a *counter* to determine how many times to run the code.

for (var i = 0; i < 10; i++>){
    document.write(i);
}

#### WHILE
Used for when you don't know how many times the code should run, the **WHILE** Loop can use any condition to determine how many times the code should run.

var i = 0;

while (i <10) {
    i++;
}
document.write(i);

#### DO WHILE
Basically the same as the **WHILE** Loop, the **DO WHILE** Loop will always run the code block once even if the condition is *false*.  This is because the code comes before the condition.

var i = 0;

do {
    i++;
} while (i <10);

document.write(i);
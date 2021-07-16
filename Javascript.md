# Javascript Notes

- JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles.

- JavaScript is a scripting or programming language that allows you to implement complex features on web pages. 

- JavaScript is a scripting language that enables you to create dynamically updating content, control multimedia, and animate images.

## alert
        - It shows a message and waits for the user to press “OK”.

        - For example:

        - alert("Hello");

## prompt
        
        - The function prompt accepts two arguments:

        - result = prompt(title, [default]);

- visitor can type something in the prompt input field and press OK. Then we get that text in the result. Or they can cancel the input by pressing Cancel or hitting the Esc key, then we get null as the result.

- The call to prompt returns the text from the input field or null if the input was canceled.

- For instance:

- let age = prompt('How old are you?', 100);

- alert(`You are ${age} years old!`); // You are 100 years old!

## confirm

- shows a message and waits for the user to press “OK” or “Cancel”. It returns true for OK and false for Cancel/Esc.

## The “if” statement

- The if(...) statement evaluates a condition in parentheses and, if the result is true, executes a block of code.

## Boolean conversion

- The if (…) statement evaluates the expression in its parentheses and converts the result to a boolean.

## The “else” clause

- The if statement may contain an optional “else” block. It executes when the condition is falsy.

## Several conditions: “else if”

- Sometimes, we’d like to test several variants of a condition. The else if clause lets us do that.

## Conditional operator ‘?’

- Sometimes, we need to assign a variable depending on a condition.

## Control flow

- The control flow is the order in which the computer executes statements in a script.

- Code is run in order from the first line in the file to the last line

## Function declarations

- A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

- The name of the function.

- A list of parameters to the function, enclosed in parentheses and separated by commas.

- The JavaScript statements that define the function, enclosed in curly brackets, {...}.

## Calling functions

- Defining a function does not execute it. Defining it names the function and specifies what to do when the function is called.

- Calling the function actually performs the specified actions with the indicated parameters. For example, if you define the function square, you could call it as follows:

## Recursion

- A function can refer to and call itself. There are three ways for a function to refer to itself:

        - The function's name
        - 
        arguments.callee
        
        - An in-scope variable that refers to the function

## Closures

- Closures are one of the most powerful features of JavaScript. JavaScript allows for the nesting of functions and grants the inner function full access to all the variables and functions defined inside the outer function (and all other variables and functions that the outer function has access to).

## for statement

- A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

- A for statement looks as follows:

- for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

- while statement
- A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

- while (condition)
   statement
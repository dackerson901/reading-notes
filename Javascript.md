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
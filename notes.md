# JavaScript Basics

JavaScript was invented by Brendan Eich in 1995. It was developed as a scripting language for the Netscape browser and later Mozilla's Firefox browser.

A scripting language is a language that is interpreted at runtime (by the browser, in the case of JavaScript), rather than requiring compilation - converting source code to machine language before the computer runs it.

Server-side languages (often called the back end) are used to program applications that run behind the scenes:

- PHP
- Java
- Python

Client-side languages work in the front end, with the script visible to the users. These reduce server load because front-end applications, like a web browser, run the programming.

- jQuery
- JavaScript
- HTML/CSS

In order to link JavaScript to a website, you must add a script tag to your html.

> Ex. Add a script tag to your html file.

## Input Process Output (IPO)

The flow of any programming application. All programs are creating in this way:

1. Input: The data required for an application to function.
2. Process: Using the input data in some way to produce desired results.
3. Output: After processing the data, display the intended result.

> Ex. Describe the process of logging into bank account in terms of IPO

input: entering your username and password.
processing: check if the credentials are correct
output: site lets you in, or tells you you've entered the wrong info

## Output: alert, console.log, .innerHTML

Alert: Display data in a dropdown window.

> Ex. Have the phrase "Hello World!" appear in an alert window.
> alert("Hello World!");

Console: Display data in the console window.

> Ex. Have the phrase "Goodbye World!" appear in the console.
> console.log("Goodbye World!");

innerHTML: Display data on a website. More on this later!

## Input: prompt and .value

Prompt: Provides a drop-down window with a field for user input.

> Ex. Ask a user to enter their age
> prompt("Enter your age:");

.value: Reads the data inside an HTML's input field. More on this later!

## Processing: Data Types

JavaScript has 3 main types of data:

1. Strings: letters, characters, white-space, words, sentences. Must always be encases in quotes ('' or "" or ``).
2. Numbers: integers, decimals (floating point numbers), negative numbers.
3. Booleans: logical true or false. More on this later.

> Ex. Give 3 examples of strings
> "Banana" `100` 'z'
> Ex. Give 3 examples of numbers
> -3 0.5 2

## Processing: Variables and Constants

In order to process data, it needs to be saved to a variable. Think of a variable as a suitcase that can hold information. A variable can hold onto one piece of data at a time, but it can be changed at any point. Variables must be declared or initialized before use using the keyword let or var.

Variables are named using a label. You choose the label name. Names should always be chosen to reflect the type of data it will store. Labels with more than 1 word should use camel-casing (e.g. thisVariable) or underscoring (e.g. this_variable).

Once you've picked the label, you use the assignment operator (=) to assign the data on the right side to the variable on the left side.

Constants are used to store values that can't be changed later in the program.

> Ex. Declare 2 variables: one to store the user's height, and the other to store the user's favorite colour.
>
> Ex. Initialize 2 variables: one to store the user's weight, and the other to store the user's name.
>
> Ex. Initialize a constant representing the capital city of Alberta. Attempt to change its value and note what happens.
>
> Ex. Assign the user's height to 6 and name to "Cloud". Display these in the console.

## String Concatenation & Template Strings

Often you will want to output a string that contains data stored in a variable.

String concatenation does this using the + operator

> Ex. Output the phrase "Cloud's height is 6 feet." using the variables in the previous example.

Template Strings require the `` quotes and using ${} to encase the variable.

> Ex. Output the phrase "Cloud lives in Alberta".
>
> Ex. Change the values of the variables and observe how the example changes.

## Comments

Comments are used to document your code. This is done to organize your code so it is easier to read and to explain particularly confusing code.

Comments are also used to have JavaScript ignore code while you are testing and debugging.

Single line comments use the // symbols while multiline comments use /_ and _/

The shortcut ctrl-/ us useful for commenting and uncommenting multiple lines of code.

> Ex. Add single and multi-line comments below. Try using the shortcut to comment multiple lines at once.

// This is a single line comment

/_
This
is
a
comment
_/

## Debugging and Testing

Computer programming is 20% programming and 80% debugging. You must have a strategy for debugging. To properly debug, you must be a detective and use console.log statements to investigate your data.

> Ex. Prompt a user for a noun, adjective, verb and a number. Create a sentence using their data in the form "The **\_** **\_\_\_\_** can **\_\_** over \_\_\_\_ kilometers!!"

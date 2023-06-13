 # HW1_Create_Readme 

 ## JS Lecture-1

 # Getting started with javascript

JavaScript is a popular programming
language that has a wide range of
applications.
JavaScript was previously used mainly for
making webpages interactive such as form
validation, animation, etc. Nowadays,
JavaScript is also used in many other areas
such as server-side development, mobile
app development and so on.

 # JAVASCRIPT RELEASES 

The ECMAScript specification is a standardized specification of a scripting
language developed by Brendan Eich of Netscape initially named Mocha, then
LiveScript, and finally JavaScript.
Learn modern JavaScript from the beginning, but without forgetting the older 


 # run JavaScript 

Because of its wide range of
applications, you can run
JavaScript in several ways:
- Using console tab of web browsers
- Using Node.js
- By creating web pages

 # 1. Using Console Tab of Web Browsers

1. Open your browser and right click in any empty area and select inspect or press F12.
2. Open the developer tools and go to Console tab. Write the Javascript code and press Enter

 # 2. Using Node.js

Node is a back-end environment for executing JavaScript
code. To run JS using Node.js, follow these steps:
1. Install the latest version of Node.js.
2. Open Visual studio code and create js file
3. Run node hello.js
4. See the result

 # 3. By creating web pages 

JavaScript was initially created to make web pages
interactive, that's why JavaScript and HTML go hand in
hand. To run JS from a webpage, follow these steps:
1. Create new folder
2. Create index.html, script.js files
3. Write shown line of codes

 # JavaScript Variables and Constants

In programming, a variable is a container (storage area) to hold data.
In Javascript there is two types of intializing variables, var and let. You can use both of them.
However, there are some differences between them.

If you are sure that the value of a variable won't change throughout the program, it's recommended
to use const .

 # Rules for Naming JavaScript Variables

1. Variable names must start with either a letter, an underscore _, or the dollar sign $
2. Variable names cannot start with numbers. For example:
```
let 1simpleText = 'Javascript is really simple';
console.log(1simpleText);
```

# CONDITIONALS
Conditional statements control behavior in JavaScript and determine whether or not pieces of code can run.

There are multiple different types of conditionals in JavaScript including:

 # CONDITION IF statment

“If” statements: where if a condition is true it is used to specify execution for a block of code.
“Else” statements: where if the same condition is false it specifies the execution for a block of code.
“Else if” statements: this specifies a new test if the first condition is false.
Now that you have the basic JavaScript conditional statement definitions, let’s show you examples of each.

Learn How to Become a Web Developer with Pluralsight Skills
If Statement Example
As the most common type of conditional, the if statement only runs if the condition enclosed in parentheses () is truthy.
<p style="font-size:22px">Example:</p>

```
if (10 > 5) {
      var outcome = "if block";
}
```
Output:

```
"if block"
```

 # CONDITION Switch statment

The switch statement evaluates
an expression, matching the
expression's value against a series
of case clauses, and executes
statements after the first case
clause with a matching value,
until a break statement is
encountered. The default clause
of a switch statement will be
jumped to if no case matches the
expression's value.

<p style="font-size:22px">Example:</p>

```
const grade = 87;

switch (true) {
	// If score is 90 or greater
	case grade >= 90:
		console.log("A");
		break;
	// If score is 80 or greater
	case grade >= 80:
		console.log("B");
		break;
	// If score is 70 or greater
	case grade >= 70:
		console.log("C");
		break;
	// If score is 60 or greater
	case grade >= 60:
		console.log("D");
		break;
	// Anything 59 or below is failing
	default:
		console.log("F");
}
```

<p style="font-size:22px">Output:</p>

```
Output
'B'
```

# LOOPS

In JS we have three type of loops:
1. For
2. While
3. Do-while

 # LOOP for

The for statement creates a loop that
consists of three optional expressions,
enclosed in parentheses and separated by
semicolons, followed by a statement
(usually a block statement) to be
executed in the loop.
The following for statement starts by
declaring the variable i and initializing it
to 0. It checks that i is less than nine,
performs the two succeeding statements,
and increments i by 1 after each pass
through the loop.

<p style="font-size:22px">Example:</p>

```
const n = 5;

for (let i = 1; i <= n; i++) {
    console.log(`I love JavaScript.`);
}
```

<p style="font-size:22px">Output</p>

```
I love JavaScript.
I love JavaScript.
I love JavaScript.
I love JavaScript.
I love JavaScript.
```

# LOOP while

The while statement creates a loop that
executes a specified statement as long as
the test condition evaluates to true. The
condition is evaluated before executing the
statement.
The following while loop iterates as long as
n is less than three.
Note: Use the break statement to stop a
loop before condition evaluates to true.

<p style="font-size:22px">Example:</p>

```
while (i < 10) {
  text += "The number is " + i;
  console.log(text);
  i++;
}
```

<p style="font-size:22px">Output</p>

```
The number is 0
The number is 1
The number is 2
The number is 3
The number is 4
The number is 5
The number is 6
The number is 7
The number is 8
The number is 9
```

# LOOP Do/while

The **do...while** statement creates a loop
that executes a specified statement until
the test condition evaluates to false. The
condition is evaluated after executing
the statement, resulting in the specified
statement executing at least once.
In the following example, the do...while
loop iterates at least once and reiterates
until i is no longer less than 5.

<p style="font-size:22px">Input</p>

```
let text = "";
let i = 0;
do {
  text += i + "<br>";
  console.log(text);
  i++;
}
while (i < 5);
```

<p style="font-size:22px">Output</p>

```
0
1
2
3
4
```

# FUNCTIONS

There are 3 ways of writing a function in JavaScript
1. FUNCTION Declaration
2. FUNCTION Expression
3. FUNCTION IIEF

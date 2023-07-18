# My research

which one's better for styling? CSS or JS

It is always said that in building a website, the HTML is for structure, CSS using for styling and presentation and JS is for bahaviour.

but what's a difference?

CSS has different classes setup and it's static on the other hand in js changing styling is one-time change and it's dynamically so won't inherit the styling changes automatically.

in CSS coding when we have a mistake in css rules or missing tag, this doesn't impact the entire web page, might break the layout but it won’t stop the site from loading. but one syntax error in JS will break entire app or lose some works.

btw what every things looks like and where should components placed are CSS. actualy JS is beyond that, when a user click on a element (button for example) what should happen after that it's by JS.

# 2

> I just wrote some note while i learning JS.

- 2 way for power numbers:
5 ** 2
Math.pow(5,2)

- For extra large or extra small numbers:
let x = 123e5;    // 12300000
let y = 123e-5;   // 0.00123

- JavaScript will try to convert strings to numbers in all numeric operations:
let x = "100";
let y = "10";
let z = x / y; -> or other operand except plus (+) that concatenate two strings

- NaN = Not a Number : typeof NaN returns number

- Infinity (or -Infinity) -> if you calculate a number outside the largest possible number : typeof Infinity returns number

- == & ===
 When using the == operator, x and y are equal.(in any type)
 When using the === operator, x and y are equal.(in same type)

- dynamically type mean -> For example, a variable can at one moment be a string and then store a number.
let message = "hello";
message = 123456;

- A BigInt value is created by appending n to the end of an integer.
const bigInt = 1234567890123456789012345678901234567890n;

- Backticks (`) allow us to embed variables and expressions into a string by wrapping them in ${…}.
alert( `the result is ${1 + 2}` ); // the result is 3

- difference between null and undefined:
null means “nothing”, “empty” or “value unknown”.
-> let age = null;
undefined mean  “value is not assigned”. 
-> let age;
   alert(age); 

- in Arrays we have these function :
myArray.push(sth);
myArray.pop();
myArray.shift(); -> like pop but remove element from begin 
myArray.unshift(sth); -> like push but add element to begin 

- random numbers:
number between 0 and 1 (not include 1) -> Math.random()
number between 0 and 20 -> Math.floor(Math.random() * 20)

- convert to integer :
if it's string -> parseInt(str)
if it's binary -> parseInt(str , 2)

- one line if else statement :
condition ? if-statement : else-statement ;

- const is read-only

- if we want to reasign a array that is const :
 don't reasign whole array at one time!
 reasign every element in that array one by one.

- if we have an object and don't want that change :
use Object.freeze(object-name) 

> I also do odin html task; for practicing html and git.
https://github.com/NzninMrdn/odin-recipes
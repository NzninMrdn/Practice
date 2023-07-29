# 1

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

- Backticks (\`) allow us to embed variables and expressions into a string by wrapping them in ${…}.
alert(\`the result is ${1 + 2}` ); // the result is 3

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

# 3 date : *1402/4/28*

> Flex

- flex : flex-grow flex-shrink flex-basis\
-> flex-basis = in row it's like with for items and in column it's like height.(also not exactly the same)\
-> we can say flex-grow is inverse of flex-shrink.\
   first one control that how the space distributed between children when they are smaller than container.(maximize viewport)\
   and the second control that how remove space when children are bigger than container.(minimize viewport)

- flex-direction : (row | column)
- justify-content : ( flex-start | flex-end | center | space-around | space-between | space-evenly)
- align-item : (stretch | center |  flex-start | flex-end | start | end | baseline | initial | inherit)
- align-self : each item change it self.

- min-with is important in flexbox.

- gap it's great for navigation header. we put this property in container.

- margin left auto is usefull for logo in navbar.

- we can change the height of container if the height of html and body is 100%. if we don't do that the 
height will be the height that container need to display it's content.

- Grid solves different problems than Flexbox.

# 4, date : *1402/4/31*

- what is Holy Grail layout?

-> It's name of specific web design page. that include header section in top, footer section at the bottom, and 3 columns in the middle that is 2 sidebar and main in between.

and also done flex odin exercise : https://github.com/NzninMrdn/css-exercises.git

# 5, date : *1402/5/1*

- I done html, css odin project : https://github.com/NzninMrdn/maybePersonal.git

# 6, date : *1402/5/3*

- invoke is fancy word for run or execute.

- built-in browser function help us coding faster, i mean dont need to write whole function and then use that, these functions couldn't written in javascript, which is written with low level sysyem language like c++. 

- i also done Rock Paper Scissors game with javascript : https://github.com/NzninMrdn/RPS.git

# 7, date : *1402/5/4*

- What's camelCase?

-> it's a way to naming variables or functions. When their names contains multiple words, here's the way for naming, the letters of first word are written completely in lowercase, for other words just the first letter of them written in upercase. This is also the way that using in clean code.

- In clean code, variables shouldn't start with verbs like : const getUserScore. This could be confuse for functions. Means that for function names. 

- When we use all caps for declaring variables?

-> When programmer absolutely sure that variable is truly consistent.


- also done javascript exercises : https://github.com/NzninMrdn/javascript-exercises.git

# 8, date : *1402/5/7*

- What's Metadata?

-> In a simple definition means data that describes data. for exapmle HTML is data but also include head that describes data like who wrote it : <meta name="author" content="Chris Mills" />

- The meta element <meta charset="utf 8" /> in html head means that this web page will render in any human language. If don't do that the page will apear messed up. This also depending on what browser you use. For example Chrome whill atoumatically fix incorrect encoding.

- <meta name="description" content="..." /> what's this kind of specifying use for?

-> A description that include the content of your web page, will has potential to apear higher in relevant
searches performed in search engines.

- What's SEO (Search Engine Optimazation)?

-> It's about site ranking. The process of making your website more visible in saerch result. Search engins maybe have some guidlines for SEO, but big search engins keep that result as a secret.

- SEO method has 3 broad classes: 
1. Technical
2. Copywriting
3. Popularity

- What's DOM (Document Object Model)?

-> It contains contents of nodes on a webpage as tree-like.

- DOM methods : 

-> Query selectors that returns refrence to that object that selected.

-> Element creation creates a new element of tag type tagName.

-> Append elements.

-> Remove elements.

-> Altering elements that when reference to an element, you can use that reference to alter the element’s own properties. 

- and start these 30 javascript exersice : https://github.com/NzninMrdn/JavaScript30.git


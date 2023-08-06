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

# 9, date : *1402/5/8*

- ok, i'm trying to creat and design cofe and resturant website.

- How user can interact with that?

-> In that website, if user sign up will has more facilities. for now just assume that user just want order food when is in that resturant. 

- At first, is shown a welcome page after that they can start ordering their food in that resturant.
They can see all the available categories of foods and when picked up one of them, they can select and add ideal item and in that category they have search option.

- Also each food has their own page that include informations and ingredients that is changeble by customer. For exapmle they can handle that how much milk or sugre they need in their late. It has like button and comment section that is helpful for other to pick their choice.

- In the bottom of page, there is spon and fork icon that they can see their orders so far.

- After they pick their choice, thay can pay the money and then there is a page that say what time their orders will prepared.

- Let's come back to home page, in that case user just sign up in, this page has navbar, footer and in main section something about that resturant like area, menu, ... 

- After that we have user page. This is contains favorite dishes(that user liked them), order history so far and comments that leave in food page.

- The user can also manage their profile and information. and also have logout option.

- I put my sketch in images foolder.

# 10, date : *1402/5/10*

- What is user flow?

-> The way of interacting user with project. what action they will do or what see after, all these have
path that start with consumer's entry point on the product, like onboarding screen or homepage until get final action or outcomes.

- That is very usefull and important to improve your product based on UX design.

- With a user flow, designer can understand what users thinking about and follow their steps.

- I put my user flow for one condition in images foolder.

# 11, date : *1402/5/11*

- When to use UX design user flow?

-> 1. Before starting your design: First thing is understanding your users so you need analyze customer.
After that, you will know how users will perform on your website or product and have how many pages or screens you need to design and how they will order in your mind.

-> 2. After finishing your design: When finished your design you should present it to your manager or colleagues. use the user flow to display how users will act on your design work, how they will get their requirements met, and how their experience is.

-> 3. Find target points that can be improved: Updating your product is actually important to improve its quality and user experience.

- What are the different types of user flows?

-> 1. Task flow: Task flow is a one-path flowchart for one specific mission. It will not show other branches and pathways. And it is frequently used in projects that all users will only follow one way.

-> 2. Flowchart: he flowchart contains several task flows. Users will take different steps for different conditions.

-> 3. Wireflow: Is more complicated. Wireflow is a better way to use it after how your users will perform and how many pages or screens you need to design are known.

-> 4. Screen-flow: Screen flow will be the same as wireflow in style. The only difference is that it consists of a high-fidelity prototype and flowchart. If you need to show how your final design works to your colleagues, screen-flow will be the appropriate method.

- My final user flows are in images foolder.


# 12, date : *1402/5/14*

- What is Sitemap?

-> A sitemap is a diagram of a website or application, that shows how pages are prioritized and linked.

- How to creat a Sitemap?

-> A sitemap consists of linked pages, each with a reference number and a label. Reference numbers help you keep track of pages even as you move on to wireframes and prototypes.

- As with any business process, creating a sitemap needs a good plan and preparation. You first need to determine what information you want to provide to the users and what role your website’s strategy should play. For example, if you run an online store, the main purpose of your site will probably be to sell your products.

- Depending on your site’s purpose, you should arrange information and navigate the user through the site to achieve the result.

- Start with the homepage, and then identify the pages that the user will go to directly from it. These should be in the second category.

- Remember to focus on convenience and a positive user experience when creating your navigation. Your site needs to be clear and easy to use and navigate. Ensure that the users can find what they are looking for and that they’re in a place that brings them closer to the goal.

- I put may Sitemap of home page and onboarding in images.


# 13, date : *1402/5/15*

- Before starting Prtotyping and Designing, we should Wireframing. It's something based on sketch, user flow and sitemap that we do earlier and more like a real project but not still yet.

- In our process to get the intended result, we improve step by step to have a site with better user experience and that's important for us to focus on those thing that user can interact with and ther satisfaction.

- I put the ordering phase wire frame in image foolder.
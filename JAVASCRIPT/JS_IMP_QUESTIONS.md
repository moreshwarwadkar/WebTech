1. Difference between Java & JavaScript
Java	JavaScript
OOP programming language	Scripting language
Compiled	Interpreted
Runs on JVM	Runs in browser/node
Used for backend, apps	Used for frontend web

2. What are JS data types?
Primitive types

String
Number
Boolean
Null
Undefined
Symbol
BigInt

Non-primitive

Object
Array
Function

3. What is Hoisting & TDZ?

Hoisting:
Variables and functions are moved to top of scope before execution.

TDZ (Temporal Dead Zone):
let and const exist but cannot be accessed before initialization.

4. Difference between Local scope, Global scope & Block scope

Local scope: Accessible only inside function
Global scope: Accessible everywhere
Block scope: Accessible only inside { } → used by let, const

5. Difference between var, let, const

var → function scoped, hoisted, can redeclare
let → block scoped, cannot redeclare
const → block scoped, cannot redeclare, cannot reassign

6. Types of popup boxes in JS

alert()
confirm()
prompt()

7. What is Closure in JS?
A closure is when a function remembers its outer scope even after outer function has returned.

8. Difference between call(), apply(), bind()
Method	Use

call()	Calls function with arguments comma separated
apply()	Calls with array of arguments
bind()	Returns new function with fixed this

9. What is a Callback function in JS?
A function passed as an argument to another function and executed later.

10. How many ways an HTML element can be accessed in JS?

getElementById()
getElementsByClassName()
getElementsByTagName()
querySelector()
querySelectorAll()

11. Difference between innerHTML vs innerText vs textContent

innerHTML: returns HTML + text
innerText: returns visible text only
textContent: returns all text (including hidden)

12. Difference between == and ===

== checks value only
=== checks value + datatype (strict)

13. Difference between for-in, for-of & forEach

for-in
Loops over keys (objects).

for-of
Loops over values (arrays, strings).

forEach
Array method to loop values.

14. In how many ways we can create object in JS?

Object literal → {}
new Object()

Constructor function

Class
Object.create()

15. Differences

(i) some() vs every()
some() → returns true if any element matches
every() → returns true if all elements match

(ii) Slice vs Splice
slice() → copy array (no change)
splice() → remove/replace (changes array)

(iii) substring vs substr
substring(start, end)
substr(start, length)

(iv) querySelector() vs querySelectorAll()
querySelector() → returns first element
querySelectorAll() → returns NodeList of all matches

(v) map(), filter(), reduce()
map() → returns new array
filter() → returns filtered array
reduce() → returns single value

16. What are ES6 features?

let, const
Arrow functions
Template literals
Classes
Spread operator (...)
Rest parameter
Modules (import/export)
Promises
Default parameters
Destructuring

17. What is Promise in JS?

A Promise represents a future value of an asynchronous task.
States:

pending
fulfilled
rejected

18. What is Promise Chaining?
Running multiple .then() one after another.

19. What are functions?
Reusable blocks of code executed when called.

20. Why are Arrow Functions used everywhere?

Short syntax
No own this
Faster to write
Good for callbacks

21. What is Object Destructuring?
Extracting values from object into variables.
const {name, age} = person;

22. What is fetch()?
Used to make API calls.
Returns a Promise.

23. What is async & await?

Cleaner way to handle Promises
async makes function return a Promise
await waits for Promise to resolve

24. What is BOM & DOM?

BOM: Browser Object Model → window, location, history
DOM: Document Object Model → HTML structure

25. Difference between Local storage & Session storage

Local Storage	Session Storage
Permanent	Clears on tab close
No expiry	Tab-based
5–10 MB	5 MB

26. What are Exports & Imports?

Used to share code between JS files.

export default
export const
import

27. Explain your project

I can prepare a perfect interview project explanation if you tell me which project (JS, HTML CSS, Django, E-commerce, To-Do, etc.).

28. try & catch to handle error

Used to handle runtime errors:

try {
   // code
} catch(err) {
   console.log(err);
}

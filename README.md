# JavaScript
JavaScript is a high-level, compiled language. It is dynamically typed It has application programming interfaces (APIs) for working with text, dates, regular expressions, standard data structures, and the Document Object Model (DOM).

# variables
Three ways to create variables
1. var
2. let
3. const

## var keyword:
`var` keyword is used when we need a variable to be declared or modified/updated.
It can be played with outside the code-block too!

```js
var a = "Hello"
var b = 1
```
We'll see about var keyword more!

## let keyword:
`let` keyword is newly introduced in ECMASCRIPT2015/ES6.
They are block scoped and the recommended way of declaring variables.
unlike `var` it cannot be redeclared (within it's scope)

```js
let a = "Hello"
let b = 10
```

## const keyword:
`const` keyword is used when you don't need the value of the variable to change/update.
`const` variables cannot be redeclared or updated, and it'll throw an error.

```js
const a = "I ❤ JS"
const = 50
```
# Conditionals:
1. if
2. if else
3. if else-if else
4. switch

## if:
```js
if (a<b){
  console.log("do this")
}
```
## if else:
```js
if (a<b){
  console.log("do this")
}
else {
  console.log("else do this")
}
```
## if else-if else:
```js
if (a<b){
  console.log("do this")
}
else if (a>b) {
  console.log("else do this")
}
else {
  console.log("else finally this")
}
```
## switch:
```js
switch(a<b) {
  case one:
    console.log("case 1 done ✔")
    break;
  case two:
    console.log("case 1 done ✔")
    break;
  default:
    console.log("default ✔")
} 
```

# Loops:
1. for
2. while
3. do-while

## for loop:
```js
let a = 10
for (let i=0; i<a; i++){
  console.log("Hello")
}
```
## while loop:
```js
let a = 20;
let n = 0;
while (n < a) {
  console.log("Looping...")
  n++
}
```
## do-while loop:
```js
let a = 20;
let n = 0;
do {
    console.log("Looping...");
    n++
} while (n < a);
```
# JS Objects:
Objects are a collection of properties in a single variable with preferably `const` declration.
An Object can contain multiple properties
```js
 const pen = {
              type:"ink", 
              model:"parker",
              color:"blue"
              };
 const anotherpen = {
                    type: "Gel",
                    model: "Trimax",
                    color: "black"
                    };
```
To access the properties of the JS Object we use `.` (dot) operator.
Let us try to access one property of the above object

```js
pen.type // ink
anotherpen.color // black
pen.model // parker
anotherpen.type // Gel
```
# Functions:
```js
function sampleGreet(name) {
  let Greet = "Hello"
  return Greet + " " + name + " 👋"
}
name = "GDSC"
sampleGreet(name)
```

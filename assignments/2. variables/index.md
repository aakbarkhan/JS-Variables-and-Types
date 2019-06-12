1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark"; //name is string
```

2. Find the error if any
```js
  var product cost = 3.45; // the product cost is invalid.
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" //right
  'Hello World" //wrong
  "Hello World' // wrong
  'Hello World' //right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man; //valid
var 1girl; //invalid
var woman3; //valid
var -girl; //invalid 
var blackDog; //valid
var 42; //invalid
var $42; //valid
var userName; //valid
var x, y, z; //valid
var x = 5, y = 6, z = 7; //valid
var x = 5 + 10 + 2; //valid
```

## Basic Operations

Mathematical Operations:

```js
var amount = 2080;
// Mathematical Operations:
// Define a new variable and store the value that is 80 less then the value of amount.
var amount = 2080;
var newAmt=amount-80;

// Define a new variable and store the value that is 200 more then the value of amount.
var amount = 2080;
var newAmt=amount+200;

// Define a new variable and store the value that is 4 times the value of amount.
var amount = 2080;
var newAmt=amount*4;

// Define a new variable and store the reminder when the value of amount is  divided by 21.
var amount = 2080;
var reminder=amount%21;
```
Logical Operation
```js
var johnAge = 45;
var markAge = 35;


// Check who is older eithe John or Mark
var johnAge = 45;
var markAge = 35;
var result=(johnAge >markAge);
alert(`${result} means john is older`);
// Check who is younger
var johnAge = 45;
var markAge = 35;
var result=(johnAge <markAge);
alert(`${result} means mark is younger`);
// Check if their age is equal
var johnAge = 45;
var markAge = 35;
var result=(johnAge==markAge);
alert(`${result} means not equal`);
// Create a new variable and assign the age of john to new variable.
var johnAge = 45;
var markAge = 35;
var newAge=johnAge;

// Check if john is equal to or greater then mark.
var johnAge = 45;
var markAge = 35;
var result=(johnAge>=markAge);
alert(`${result} means greater`);
// Check if john is less then or equal to mark.
var johnAge = 45;
var markAge = 35;
var result=(johnAge<=markAge);
alert(`${result} means lesser then john`);

// Calculate the average age of john and mark and assign to a new variable.
var johnAge = 45;
var markAge = 35;
var result=(johnAge+markAge);
alert(`${result/2} `);
```
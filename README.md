# JS-Math

## Description
JS-Math is a library of math functions that allows you to perform common math operations on numbers and arrays.

## Installation
1) First install nodejs https://nodejs.org/
2) Verfiy nodejs and npm are installed with commands in the terminal, <code>node -v</code> and <code>npm -v</code>
3) Run the command <code>npm install math</code>

## Usage
To use JS-Math import the module in your javascript file 
```javascript
const jsMath = require('math');
```
To run the file, run the command <code>node file_name.js</code>

## Functions
There are nine basic functions that can be utilized: samesign, copysign, add, sum, mul, prod, factorial, gcd, and lcm.

#### Samesign
The samesign function takes two numbers as arguments and returns a boolean whether they have the sign same.
```javascript
jsMath.samesign(4, 5); //samesign(4, 5) => returns: true
```
#### Copysign
The copy sign function takes two numbers as arguments and returns the first argument with the same sign as the second argument.
```javascript
jsMath.copysign(-3, 6); //copysign(-3, 6) => returns: 3
```
#### Add
The add function takes two numbers as arguments and returns their sum.
```javascript
jsMath.add(15, 11); //add(15, 11) => returns: 26
```
#### Sum
The sum function takes an array of numbers as an argument and returns their sum.
```javascript
jsMath.sum([2,3,4]); //sum([2,3,4]) => returns: 9
```
#### Mul
The mul function takes two numbers as arguments and returns their product.
```javascript
jsMath.mul(3,7); //mul(3,7) => returns: 21
```
#### Prod
The prod function takes an array of numbers as an argument and returns the product of the elements in the array.
```javascript
jsMath.prod([8,9,23]); //prod([8,9,23]) => returns: 1656
```
#### Factorial
The factorial function takes a number as an argument and returns the [factorial](https://en.wikipedia.org/wiki/Factorial).
```javascript
jsMath.factorial(7); //factorial(7) => returns: 5040
```
#### GCD
The gcd function takes two numbers as arguments and returns their [greatest common divisor](https://en.wikipedia.org/wiki/Greatest_common_divisor).
```javascript
jsMath.gcd(126, 48); //gcd(126, 48) => returns: 6
```
#### LCM
The lcm function takes two numbers as arguments and returns their [least common mulitiple](https://en.wikipedia.org/wiki/Least_common_multiple).
```javascript
jsMath.lcm(24, 36) //lcm(24, 36) => returns: 72
```

## Coffeescript
Additionally, there is a coffeescript file that can be compiled to a javascript file named math.js.

To install coffeescript globally run the command <code>npm install -g coffeescript</code>

To verify coffeescript is installed globally run the command <code>coffee -v</code>.

To compile the coffeescript file run the command <code>coffee -c math.coffee</code> in the same directory as the math.coffee file. This will produce a math.js file.

To read more about coffeescript visit https://coffeescript.org/

## License

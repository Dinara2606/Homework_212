# Types of JavaScript Operators
## Arithmetic Operators
Used to perform arithmetic on numbers

| **Operator**    | **Description** |
| -------- | ------- |
| +  | Addition  |
| - | Subtraction     |
| *    | Multiplication    |
|**|Exponentiation|
|/	|Division|
|%	|Modulus (Division Remainder)|
|++|Increment|
|--|Decrement|
## Assignment Operators
Assignment operators assign values to JavaScript variables.

The Addition Assignment Operator (+=) adds a value to a variable.
|**Operator**|	**Example**|	**Same As**|
|--------|--------|---------|
=	|x = y|	x = y
+=	|x += y|	x = x + y
-=	|x -= y|	x = x - y
*=	|x *= y|	x = x * y
/=	|x /= y|	x = x / y
%=	|x %= y|	x = x % y
**=	|x **= y|	x = x ** 
## Comparison Operators
|**Operator**|	**Description**|
|--------|--------|
==	|equal to
===	|equal value and equal type
!=	|not equal
!==	|not equal value or not equal type
|>	|greater than|
<	|less than
|>=|greater than or equal to|
|<=|less than or equal to|
|?|ternary operator|
## String Operators
All the comparison operators above can also be used on strings.

Note that strings are compared alphabetically.

When used on strings, the + operator is called the concatenation operator.

If you add a number and a string, the result will be a string!

## Logical Operators
Operator|	Description
|------|----------|
&&|	logical and
||||	logical or|
!|	logical not
## Bitwise Operators
Bit operators work on 32 bits numbers.

Any numeric operand in the operation is converted into a 32 bit number. The result is converted back to a JavaScript number.
# JavaScript dynamic types
JavaScript has dynamic types. This means that the same variable can be used to hold different data types:

let t = 16;			// t is a number

let t = "Teresa";	// t is a string

let t = true;		// t is a Boolean

let t;				// t is undefined

In dynamically typed languages variables have the ability to change their data type during runtime. This allows for adaptability in situations.

Another benefit is the ease of use that dynamic typing provides. Unlike static typed languages developers in dynamic typed languages don’t need to explicitly specify data types when coding. This simplifies the coding process. Makes it more intuitive.

Runtime variable type re-checking is another feature offered by dynamic typing. During runtime the type of a variable is checked which means any errors related to type mismatches might only be discovered at that point. While this can lead to issues it also offers flexibility in handling data types on the fly.

## Typeof operator
**typeof** operator is used to find the data type of a JavaScript variable.

typeof "John"                 // Returns "string"

typeof 3.14                   // Returns "number"

typeof NaN                    // Returns "number"

typeof false                  // Returns "boolean"

typeof [1,2,3,4]              // Returns "object"

typeof {name:'John', age:34}  // Returns "object"

typeof new Date()             // Returns "object"

typeof function () {}         // Returns "function"

typeof myCar                  // Returns "undefined" *

typeof null                   // Returns "object"

## How To Convert Data Types in JavaScript

**String() or n.toString()** is used to convert values to strings 

**Number()** method is used to convert values to a number data type

 **Boolean()** methid is used to convert numbers or strings to Boolean values

Example, 

let a = 2001;

console.log(typeof a); // Output:number. At this point, the variable a is assigned the numerical value of 2001, which we have confirmed to be a number.

a = String(a);	// "2001" let’s reassign a to its string equivalent and then use typeof to confirm that we have successfully converted the variable’s value from a number to a string.

console.log(typeof a); // Output: string. We have confirmed that a was reassigned to be equivalent to a string value following the data type conversion.


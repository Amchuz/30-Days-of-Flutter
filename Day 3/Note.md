# Dart Programming
<br />

<p align="center">
<img src="https://miro.medium.com/max/624/1*BxEDsPTfeAU4BbWjZLDaqg.png">
</p>
<br/>
  
Dart is an open-source object-oriented programming language with C-style syntax developed by Google in 2011. Dart is a compiler-based language so we pass the code through compiler phrases and then transfer it into machine code. The purpose of this programming language is to create a frontend user interfaces for the web and mobile apps. It is inspired by programming languages such as C#, Javascript, Java, etc. It supports most of the common concepts of programming languages like classes, functions, interfaces, array and it supports collection which is used to replicate the data structure such as arrays, generic, etc. 
  
Dart does not have explicit keywords like public, private with functions but instead uses underscores to differentiate between public and private functions. It saves a lot of time and improves code simplicity by a long margin. One of the most import features of Dart is a named constructor. You can make multiple constructors in Dart with different names which allow clarity in what the constructor is actually initializing.
  
You can use <a href="https://dartpad.dev/">DartPad</a> an IDE for running dart program.
  
<img src="https://dart.dev/assets/dartpad-hello-209465dbed5b3be402b0fd2b4e152d1e4493c2651572c4988b8fa80eab29136b.png" height=450 width=750>
  
You can also run sample programs given at the top right side of the page. 
  
## Hello World!
  
Every app has a main() function. To display text on the console, you can use the top-level print() function :
  
```
void main() {
print(‘Hello, World!’);
} 

Output: Hello, World!
```
## Data Types :
 
There are mainly 4 data types :
- Numbers (num,int,double)
- Strings
- Boolean
- Object
  
### Numbers
  
Numbers used for representing numeric literals. The number dart comes in two types:

- Integer — It is represented using the int keyword. Integer values represent non-fractional values without a decimal point. For example — ‘16’
- Double — It is represented using the double keyword. Double values represent fractional numeric values with decimal points. ’16.18’
  
```
void main() {
int a;
a=2;
print("Value of a is $a");
} 

Output: Value of a is 2
```
  
```
void main() {
double b=162.5;
print("My height is $b cm");
} 

Output: My height is 162.5 cm
```
```
void main() {
num b=6161131110;
print("Secret code is $b");
} 

Output: Secret code is 6161131110
```
  
### Strings
  
Used to define text in single(') or double(") quotation mark. Strings represent a sequence of characters. It is used for storing the data like name, address etc. It is represented using String keyword.
  
```
void main() {
String name="Amchuz";
print("My name is $name");
} 

Output: My name is Amchuz
```
  
### Boolean
  
The Boolean data types represent Boolean values true and false. Dart uses the bool keyword to represent a Boolean value.
  
```
void main() {
bool c=true;
print("So the answer is $c");
} 

Output: So the answer is true
```
  
### Objects
  
The data types **list** and **map** are used to represent a collection of objects. A List is an ordered group of objects. The List data type in Dart is synonymous to the concept of an array in other programming languages. The Map data type represents a set of values as key-value pairs. The dart: core library enables creation and manipulation of these collections through the predefined List and Map classes respectively.
  
### Dynamic Type
  
Dart is an optionally typed language. If the type of the variable is not explicitly specified, the variable’s type is dynamic. The dynamic keyword can also be used as a type annotation explicitly.
  
## Variables and Functions :
  
A **variable** is a named space in the memory that stores values. It act as a container for values in a program. Variable names are called identifiers. \
Naming rules for identifiers are:
  
- Identifiers cannot be keywords.
- Identifiers can contain alphabets and numbers.
- Identifiers cannot contain spaces and special characters, except the underscore ‘_’ and dollar sign ‘$’.
- Variable names cannot begin with a number.
  
eg: var my =16;
  
Here, 'my' is a variable that stores an integer value 16. We can give it int and double. Since dart has a feature called Type Inference, which infers the types of values.

**Functions** are a set of statements that performs a specific task. These are the logical blocks of code that are reusable, maintainable, and readable. It contains the function name, return type, and parameters.

eg:
  
```
num add(num a, num b) {
return a + b;
}
var x = 30;
var y = 20;
var total = add(x, y);
```
## Operators :
  
An expression is a special kind of statement that evaluates to a value. Every expression is composed of
  
- Operands − Represents the data
- Operator − Defines how the operands will be processed to produce a value.
  
Consider the following expression – "2 + 3". In this expression, 2 and 3 are operands and the symbol "+" (plus) is the operator.
Different operators are :
  
1. Arithmetic Operators
2. Equality and Relational Operators
3. Type test Operators
4. Bitwise Operators
5. Assignment Operators
6. Logical Operators
  
### 1. Arithmetic Operators
  
Operator | Meaning
| :---: | :---: 
\+ | Add 
−  | Subtract
-expr | Unary minus, also known as negation (reverse the sign of the expression)
\* | Multiply
/ | Divide
~/ | Divide, returning an integer result
% | Get the remainder of an integer division (modulo)
++ | Increment
-- | Decrement
  
### 2. Equality and Relational Operators
  
Operator | Description | Example
| :---: | :---: | :---: 
\> | Greater than | (A > B) is False
< | Lesser than | (A < B) is True
\>= | Greater than or equal to | (A >= B) is False
<= | Lesser than or equal to | (A <= B) is True
== | Equality | (A==B) is False
!= | Not equal | (A!=B) is True
  
### 3. Type test Operators
  
Operator | Meaning
| :---: | :---:
is | True if the object has the specified type
is! | False if the object has the specified type
  
### 4. Bitwise Operators
  
Operator | Description | Example
| :---: | :---: | :---
Bitwise AND | a & b | Returns a one in each bit position for which the corresponding bits of both operands are ones.
Bitwise OR | a \| b | Returns a one in each bit position for which the corresponding bits of either or both operands are ones.
Bitwise XOR | a ^ b | Returns a one in each bit position for which the corresponding bits of either but not both operands are ones.
Bitwise NOT | ~ a | Inverts the bits of its operand.
Left shift | a ≪ b | Shifts a in binary representation b (< 32) bits to the left, shifting in zeroes from the right.
Signpropagating right shift | a ≫ b | Shifts a in binary representation b (< 32) bits to the right, discarding bits shifted off.
  
### 5. Assignment Operators
  
Operator | Description
| :---: | :---: 
= (Simple Assignment ) | Assigns values from the right side operand to the left side operand. <br> Ex:C = A + B will assign the value of A + B into C
??= | Assign the value only if the variable is null
+= (Add and Assignment) | It adds the right operand to the left operand and assigns the result to the left operand. <br> Ex: C += A is equivalent to C = C + A
─= (Subtract and Assignment) | It subtracts the right operand from the left operand and assigns the result to the left operand. <br> Ex: C -= A is equivalent to C = C – A
\*= (Multiply and Assignment) | It multiplies the right operand with the left operand and assigns the result to the left operand. <br> Ex: C \*= A is equivalent to C = C \* A
/=(Divide and Assignment) | It divides the left operand with the right operand and assigns the result to the left operand.
  
### 6. Logical Operators
  
Operator | Description | Example
| :---: | :---: | :---:
&& | And − The operator returns true only if all the expressions specified return true | (A > 10 && B > 10) is False.
\|\| | OR − The operator returns true if at least one of the expressions specified return true | (A > 10 \|\| B > 10) is True.
! | NOT − The operator returns the inverse of the expression’s result. For E.g.: !(7>5) returns false | !(A > 10) is True.
  
### Conditional Expressions
  
Dart has two operators that let you evaluate expressions that might otherwise require ifelse statements 
  
condition ? expr1 : expr2
  
If condition is true, then the expression evaluates expr1 (and returns its value); otherwise, it evaluates and returns the value of expr2.
expr1 ?? expr2. If expr1 is non-null, returns its value; otherwise, evaluates and returns the value of expr2 
  
```
void main() { 
   var a = null; 
   var b = 12; 
   var res = a ?? b; 
   print(res); 
}

Output : 12
```
  
## Decision Making :
  
Statement | Description | Example
| :---: | :--- | :---
if statement | An if statement consists of a Boolean expression followed by one or more statements. | if(a=b){ <br> sum=a+b <br> }
If...Else Statement | An if can be followed by an optional else block. The else block will execute if the Boolean expression tested by the if block evaluates to false. | if(a=b){ <br> sum=a+b <br> } <br> else { <br> sum = a <br> }
else…if Ladder | The else…if ladder is useful to test multiple conditions. Following is the syntax of the same. | if(a=b){ <br> sum=a+b <br> } <br> else if(b>a) { <br> sum=b <br> } <br>else { <br> sum = a <br> }
switch…case Statement | The switch statement evaluates an expression, matches the expression’s value to a case clause and executes the statements associated with that case. | switch(condition){ <br> case 1 : {statements} <br> case 2 : .... <br> ... <br> }
  
## Loops :
  
Loop | Description
| :---: | :---
for loop | The for loop is an implementation of a definite loop. The for loop executes the code block for a specified number of times. It can be used to iterate over a fixed set of values, such as an array
for…in Loop | The for...in loop is used to loop through an object's properties.
while Loop | The while loop executes the instructions each time the condition specified evaluates to true. In other words, the loop evaluates the condition before the block of code is executed.
do…while Loop | The do…while loop is similar to the while loop except that the do...while loop doesn’t evaluate the condition for the first time the loop executes.
  
## Comments :
  
These are non-executable code. These are used to provide information about the projects, variables or an operation.
There are three types of comments in dart:
  
1. Make format comment (//) for single-line comment
2. Block Comments (/*…*/) for multi-line comment
3. Doc comments (///) used for members and type

-----------------------------------------------------------------------------------INCOMPLETE--------------------------------------------------------------------------------------------

**Sources are available at README.md**

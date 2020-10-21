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

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
  
 

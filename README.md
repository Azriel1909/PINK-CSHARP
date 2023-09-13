# CSHARP GUIDE

```C#
// Console.WriteLine("Hello World!");
Console.WriteLine("Hello World!");
Console.WriteLine("My name is Ximena!");
Console.Write("Congratulations!");
Console.Write(" ");
Console.Write("You wrote your first lines of code.");
```

## Characteristics 
1. Case sensitive language
#### Console.WriteLine
To print an entire message to the output console.
#### Console.Write
Prints another message to the same line.

## Declare Variables

A literal is a *hard-code* value. Hard-coded values are values that are constant and unchanged throughout the execution of the program. 

> When you need to work with data that isn't hard-coded, you'll declare a variable.

### What is a variable?
A variable is container fir storing a type of value. Variables are important because their values can change, or vary, throughout the execution of the program. 

> Variables can assigned, read, and changed.

A variable name is a human friendly label that the compiler assigns to a memory address. When you want to store or change a value in that memory address, or whenever you want to retrieve the stored value, you just use tha variable name you created.

## How to declare a variable?

First of all you have to declare the *data type* of a variable and them give it a name.


```C#
string firstName;
```

## Name rules and conventions
1. Can contain alphanumeric characters and underscore character.
2. Do not use # symbol or $ symbol.
3. Variables names must begin with an alphabetical letter or an underscore, not a number.
4. Important! Variable names are case-sensitive

### Conventions for variables
1. Variables should use camel case.
2. Variables names should begin with an alphabetical letter.
3. Variables names should be descriptive and meaningful.
4. Variables names should be one or more entire words appended together, do not use contractions or abbreviations.
5. Variables names should not include the data type of the variable.


```C#
char userOption;

int gameScore;

decimal particlesPerMillion;

bool processedCustomer;
```

### Creating your 1st variable
```C#
// Declare a variable
string firstName;
// Then you assign a value to the variable
firstName = "Bob";
// We can print the value
Console.WriteLine(firstName);
```

### Reassign the value of a variable
You can reassign the variable as many times as you want.

```C#
string firstName;
firstName = "Bob";
Console.WriteLine(firstName);
firstName = "Liem";
Console.WriteLine(firstName);
firstName = "Isabella";
Console.WriteLine(firstName);
firstName = "Yasmin";
Console.WriteLine(firstName);
```

### Implicitly typed local variables
An Implicitly typed local variable is created by using the **var** keyword followed by a variable initialization.

```C#
var message = "Hello world!";
```

## What is a programming language?
Programming let you write instructions that you want the computer to carry out. A programming language's job is to allow a human to express their intent in a human-readable and understandable way.

1. The instructions you write in a programming language are called *Source Code*.
2. The *Source* 1st must be compiled into a format that the computer can understand.

### What is compilation?
A special program called a **compiler** converts your source into a different format that the computer's Central Processing Unit (CPU) can execute.

#### What does code need to be coded?
The CPU understands instructions that are expressed by turning thousands or millions of tiny switches either on or off.

> Translating your human-readable instructions into a computer-understandable set of instructions.

### What is syntax?
1. When the phrase is surrounded by double-quotation marks in your C# code, it's called a literal string.
2. The Console part is called a class. Classes "own" methods; or you could say that methods live inside of a class.
   1. Think a class as a way to represent an object. 
3. The period is the member access operator. In other words, the dot is how you "navigate" from the class to one of its methods.

## Declare Implicitly Typed Local Variables
A Implicitly Typed Local Variable is created by using the ```var``` keyword followed by initialization.

The ```var``` keyword tells the C# compiler that the data type is implied by the assigned value. After the type is implied, the variable acts the same as if the actual type had been used to declare it.

> Variables using the ```var``` keyword must be initialized

## Why use the ```var``` keyword?
When you begin developing code for a task, you may not immediately know what data type to use. Using var can help you develop your solution more dynamically.
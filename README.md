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

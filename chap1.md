## Chapter 1: Basics

### First Program

`#include <iostream>` is importing the iostream package

`using namespace std;` uses the standard namespace so it pulls the functions/objects that we use from that namespace

`int main()` is run for all cpp programs

`cout` is an object that uses `<<` to insert `Hello World` as the input (does not add a new line; for that you have to use `\n`)
- `std::cout` also works if the namespace is not declared
- `cout << "Hello World" << \n\n` also adds a new line
- `cout << "Hello World" << endl` also adds a new line

Comments with `//` or `/*  */`

### Variables
`int` - stores integers (whole numbers), without decimals, such as 123 or -123

`double` - stores floating point numbers, with decimals, such as 19.99 or -19.99

`char` - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes

`string` - stores text, such as "Hello World". String values are surrounded by double quotes

`bool` - stores values with two states: true or false

To create a variable the syntax is `type variableName = value;`

Multivariable declaration: `int x = 5, y = 6, z = 7;`

`const` type variables can never be reassigned

### User Input

```cpp
int x;
cout << "Enter a number:";
cin >> x;
cout << "Your number is: " << x;
```

`<<` is the extraction operator







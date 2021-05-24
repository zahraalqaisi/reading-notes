# Operators:

 ## types of operators:

 - Assignment operators

 assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=),

 - Comparison operators

 compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values

 - Arithmetic operators

 An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/).

 - Bitwise operators

 A bitwise operator treats their operands as a set of 32 bits (zeros and ones), rather than as decimal, hexadecimal, or octal numbers.

 - Logical operators

 Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. However, the && and || operators actually return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value

 - String operators

 In addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings.

 - Conditional (ternary) operator

  the only JavaScript operator that takes three operands. The operator can have one of two values based on a condition

 - Comma operator

 The comma operator (,) evaluates both of its operands and returns the value of the last operand. This operator is primarily used inside a for loop, to allow multiple variables to be updated each time through the loop

 - Unary operators

 A unary operation is an operation with only one operand


 - Relational operators

 compares its operands and returns a Boolean value based on whether the comparison is true.


 # Loops and iteration:

 

Loops offer a quick and easy way to do something repeatedly

There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times

There are various situations that are more easily served by one type of loop over the others.

### The statements for loops:

- for statement:

repeats until a specified condition evaluates to false


- do...while statement:

The do...while statement repeats until a specified condition evaluates to false.


- while statement:

A while statement executes its statements as long as a specified condition evaluates to true.


- labeled statement:

A label provides a statement with an identifier that lets you refer to it elsewhere in your program.


- break statement:

Use the break statement to terminate a loop, switch, or in conjunction with a labeled statement.


- continue statement:

The continue statement can be used to restart a while, do-while, for, or label statement.


- for...in statement:

The for...in statement iterates a specified variable over all the enumerable properties of an object. For each distinct property, JavaScript executes the specified statements


- for...of statement:

The for...of statement creates a loop Iterating over iterable objects (including Array, Map, Set, arguments object and so on), invoking a custom iteration hook with statements to be executed for the value of each distinct property.
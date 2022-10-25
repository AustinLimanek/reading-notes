# Class 01

[Journal Home](README.md)

Current Readings:

1. [Java Basics](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/index.html)
2. [Compiling](https://www.reddit.com/r/explainlikeimfive/comments/233dq5/eli5_what_does_it_mean_to_compile_code/)
3. [XKCD: Compiling](https://xkcd.com/303/)
3. [Reading Java Documentation](https://www.dummies.com/category/articles/java-33602/)

## Reading Notes

### Java Basics

The basic components of the Java language include variables, objects, operators, expressions, statements, blocks, and control flow statements.

Inside the concept of variables there are fields, methods, and types, which are all considered members - I need some concrete examples for this to stick better in my mind.

Operators have a set precedence that define the order in which they are considered by the compiler. The table on the "operator" page will be a useful resource for when distinctions need to be made.

Expressions are made up of "variables, operators, and method invocations" and they compute to a single value. The value is the output of the expression. A statement is a unit of expression. A block is a collection of zero to n statements that follow a set syntax and have balanced curly braces.

Java has more control flow statements than I am used to in JavaScript. However, from my time using C++ the additional control flows look vaguely familiar. They are:

- (if-then, if-then-else, switch)
- (for, while, do-while)
- (break, continue, return)

This is likely not an exhaustive list, since there are other syntax used for at lease some of these. I am unfamiliar with `continue`, `switch`, and `do-while`. The latter I have seen been never used.

### Compiling

Compilers transcribe the human understandable code such as Java into binaries such that the computer can turn on and off transistors to complete logic gates. This process allows for pure calculation to occur efficiently and quickly.

As XKCD showed in it's cartoon, compiling can take a good amount of time and is a common part of the programming cycle.

### Reading Java Documentation

This section summarizes many of the most often used features of the Java language and defines many of the terms. This is a great resource to reference in the coming weeks. In addition, there are several other articles that go into more detail on error messaging, word generation, and how to print images, amongst other topics.

### Things I want to know more about

I would like to understand more about how primitives are different than other parts of the language. Why are objects not a primitive? Does this mean that an object is made up of the eight primitives of Java. In addition, how do they relate to the write, read, delete, left, right operations of all computers?

## Questions

### What does "strong typed" mean?

This means that a variable needs to have a type when it fills a field. For example, an array needs to have a certain type. This is different than JavaScript, which can have a variable defined without a type.

### Explain to a non-technical friend the difference in how compilation works in Java and JavaScript.

Compilation in Java follows a transcription schema, where the syntax is 1-to-1 converted into javabyte or close to machine code and then converted into binary. However, JavaScript uses a interpreter that allows for more "messy" code to be written.

&copy; 2022, NoMichi

# Class 03

[Journal Home](README.md)

Current Readings:

1. [Primitives vs. Objects](https://www.baeldung.com/java-primitives-vs-objects)
2. [Exceptions in Java](https://docs.oracle.com/javase/tutorial/essential/exceptions/index.html)
3. [Using Scanner to read in a file in Java](https://docs.oracle.com/javase/tutorial/essential/io/scanning.html)

## Reading Notes

### Primitives vs. Objects

Primitives and wrappers take up different amount of space in memory. Wrappers tend to take up more space, however, `long` and `float` take up less space in their `wrapper` form. The size difference becomes important when data types are stored in arrays. In addition, look up times can take much longer when the wrapper data types are used as opposed to the primitives.

### Exceptions in Java

Exceptions are used to catch error when they occur in the program. `try` `catch` and `finally` are the blocks that are used to actually deal with the error if it does occur. Exceptions can be chained in order to provide more information to the user or other programmers (or even the actual programmer) when there is an error. 

> Definition: An exception is an even, which occurs during the execution of a program, that disrupts the normal flow of the program's instructions.

### Using Scanner to read in a file in Java

The scanner is an API that works to break down input information into single tokens that can be more easily managed. This tokens are associated with bits of data for ease of use. In short, a file can be uploaded and read by Java by using scanner. If the tokens produced by the scanner is not in the correct form then they can be altered using the formatting object.

## Things I want to know more about

&copy; 2022, NoMichi

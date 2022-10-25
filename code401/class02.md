# Class 00

[Journal Home](README.md)

Current Readings:

1. [Java Imports](https://www.programiz.com/java-programming/packages-import)
2. [Different types of loops in Java](https://www.baeldung.com/java-loops)
3. [Java Arrays](https://www.tutorialspoint.com/java/java_arrays.htm)

## Reading Notes

### Java Imports

In Java you can import packages that contain methods that have been written and have pre-defined functionality. You import them by using `import java.name.AnotherName` if you want to import all of the methods in a package then you would write `import java.name.*`. You can also write your own packages by writing package and the desired name on the top of the script. The file structure is also mentioned in detail. Use this a future reference.

### Different types of loops in Java

There are four major loop types in Java: `while`, `for`, `for-each`, and `do`. Each will execute until their boolean conditional reaches false.

### Java Arrays

Arrays in Java are a set length. In addition, the arrays must hold all of the same type. You initialize an array using `double[] myList` this is an array filled with `double` type numbers and the array is called `myList`. You then 'create' the array by using the `new` operator. For example, `arrayRefVar = new double[7]` this would be an array of length 7 and filled with numbers with the `double` type and possessing the name `arrayRefVar`. Or you can use the line `double[] example = {1.1,1.2,1.3,1.4,1.5,1.6,1.7}` as a way to create the same length and type array. However, you hard code the elements in the array for this case.

`.length` is a property that outputs the length of an array. `printArray` is a built in method that accepts an array as an input and then print each element to the console. `equals` compares the length and corresponding values of two arrays. `fill` takes in an empty array and then fills the array with some given value. `sort` is another good method that sorts the elements in the array in ascending order.

## Questions

### Which loops use a loop counter

### Describe 3 built-in methods for Arrays

- `.length` is a property that outputs the length of an array.
- `printArray` is a built in method that accepts an array as an input and then print each element to the console.
- `equals` compares the length and corresponding values of two arrays.
- `fill` takes in an empty array and then fills the array with some given value.
- `sort` is another good method that sorts the elements in the array in ascending order.

### Use an analogy to explain Built-In packages. Give examples

Some of the older versions of the iPod had pre-downloaded songs because Steve Jobs felt like everyone should have access to certain songs. These songs were assumed to be useful and would improve the experience of the iPod user. This is similar to built-in packages. The `Java` editions have different built-in packages. Each version has engineers that assume that certain packages will be used so much that the decrease in efficiency or stored memory is worth is so that people will not have to remember or type the import statements so much. This saves time for the downside of either storage or efficiency.

## Things I want to know more about

The `equals` is an interesting method that seems quite powerful. I would like to see more case uses of this method.

What are the most commonly imported packages the typical programmers use. Is there a downside of importing packages. Does the import slow the program down?

&copy; 2022, NoMichi

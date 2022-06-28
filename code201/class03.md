# Class 3

[Journal Home](README.md)

Current Readings:

1. [Ordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
2. [Unordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
3. [The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
4. [Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
5. [Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
6. [Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
7. [Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

## Reading Notes

### Ordered Lists

You can change the type of bullet, either numbered, lettered, or roman. There might be others as well. One can also change the line-height, starting point: `start=4`, and margin: for an indent. There is also the ability to use the reverse attribute.

### Unordered Lists

Compact is an old, deprecated attribute of the unordered list. line-height: 80% does the same thing. There are different types: `circle`, `disc`, and `square`.

### The Box Model

The two basic box types are block and inline. Block makes a new line for the content and will push other objects away if you change the vertical padding, margin, and border. However, for inline these vertical attribute values will not be respected. The location where the display is changed applies to the children inside the given element being manipulated by CSS. Only the immediate children are impacted by the display modification.

Flex and grid are two alternative methods of organizing the content of a page.

### Arrays

Arrays are very useful objects in JS. They have many helpful data manipulation methods that can be used to sort through long lists of data. The .push() allows one to append an array and unshift() allows for the addition to occur at the beginning of the array. pop() removes the last element and shift() removes the first item. Splice() removes a given index (1 or # after the index including the index.). Any array has useful properties too. The .length allows for the length to be determined. The method map() provides a function that each element will be fed through. filter() eliminates any element that does not have a truthy value on return from a given function.

### Operators and Expressions

Operators can be either unary, binary, or ternary. JS has only one ternary operator, which was already introduced and discussed in an earlier reading. There are shorthand notation for a lot of the operators because they are used so often. Operators are often used in expressions.

### Conditionals

Conditionals are used to determine the truth value between ultimately two different truth values. If the expression in the conditional is true then code will execute, false the else code will be executed.

### Loops

Loops are great for working through an array. for...of can be used as shorthand to make it through the whole array without i notation.

This article gives a great example of how to manipulate an array of complex information and compare it to a user input information.

### Things I want to know more about

What do you can the process of putting the name of a function into a method such as map or filter?

## Answers to Questions

1. Used primarily for what the points need to have a specific order. You could always have a best of list or directions that require previous steps to occur first.
2. You use the type attribute and then either use square, circle, or disc as string values.
3. Unordered list is more universal and can also be used to contain other elements in a convenient way. Ordered list is more likely used when order matters, for example a best of or a direction set.
4. You can use the type attribute and then use the following values for their defined outcomes:

>a, for lowercase;
>A, for uppercase; i for lowercase Roman numerals;
>I for uppercase Roman numerals;
>1, for numbers(default).

1. The henchman is metastasis, the margin. It spreads outwards and moves into new locations outside the border of cancer, the padding. The content has been changed by cancer and the metastasis.
2. The four parts are the marin, border, padding, and content.

JS:

1. Strings, numbers, objects, and other arrays
2. Yes, this is a valid array
3. *=, +=, /=, %=, and **=
4. The value will be a string: '10dog'. The false has a numerical value of 0. The concatenation of 10 and dog results in the coercion of a as the number 10 to the string '10'.
5. When you only want to allow for a code block to execute only when a certain number of clicks has occurred.
6. When you want to read every element of an array, it is common to use a loop to iterate through each one for a given code block.

&copy; 2022, NoMichi

- [Class 00: ](code000/class00.md)
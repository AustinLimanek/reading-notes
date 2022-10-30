# Class 06

[Journal Home](README.md)

Current Readings:

1. [Java OO Tutorial (review Object and Class, read the rest)](https://docs.oracle.com/javase/tutorial/java/concepts/)
2. [Java Static Keyword](https://www.programiz.com/java-programming/static-keyword)
3. [Java Singleton Class](https://www.programiz.com/java-programming/singleton)

## Reading Notes

### Java OO Tutorial

Data encapsulation is a fundamental principle of object oriented programming. This means that fields are not able to be accessed without calling method in the class of that object. This can also be described as information hiding.

Objects are an instance of the class of objects they belong to. For example, a Tesla model S with the a given license plate is an instance of the Tesla model S class. Encapsulation allows for changes to the fields to be controlled by conditionals. Exception pointers can be used to alert the user of an error.

In our previous example, the brand Tesla car would be the superclass for the Tesla model S class. This would allow for each of the models to share common state and behavior by inheriting state and behavior from the superclass Tesla car.

However, documentation is important when using superclasses and inheritance to classes because the state of the fields and methods of the superclass will not be in the code for the "sub"classes.

An interface is a template of empty methods that need to be filled if it is going to be implemented. You use the `class SpecificName implements GeneralName` to define a new class from an interface. The compiler holds the programmer to a contractual standard.

### Java Static Keyword

The static keyword can be used for methods in a class that the programmer wants to use without requiring an instance to be called. Thus, a class method can be called directly `ClassName.methodName()` would work as a method call. This would be in the class of `ClassName instanceName = new ClassName; instanceName.method();` if the instance is not necessary than there is no reason the method needs to not be static. `Math` is a class that has a lot of static methods, thus the methods such as `Math.PI`, `Math.E`, and `Math.round()` can all be used in other classes.

### Java Singleton Class

The singleton is a design pattern such that an object can only be constructed within a class and then accessed from a method call outside of the class. This is done if you only want on instance of a class. That is, only one object for a given class. This could be applicable for a public database.

However, singletons go against the reusable code principle and issues with testing can arise because the state of the instance may change from test to test. There is no fresh instance to test. Thus, the order of the tests matter.

## Questions

1. What is the difference between an Object and a Class in Java?

    A class is a definition or library of fields and methods that can be used throughout the application depending on whether public or private is used. An object is an instance of a class and will use the methods and fields in the class that it is from, at least for those it has access to.

2. What is a Design Pattern? Describe one or two with analogies from your previous work experience.

    This is a way in which information is organized in a consistent way over several instances. In code, this means that classes and objects will inherit in a particular way. For tutoring, we had a design pattern of checking the students skyward, taking in a subjective of their assignments, and then tutor on required material.

3. Static methods are also called what? Why?

    They are also called class methods because when calling these methods the static method is on the class name and does not require an instance of the class to be called on.

## Things I want to know more about

&copy; 2022, NoMichi

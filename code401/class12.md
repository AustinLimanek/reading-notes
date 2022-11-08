# Class 11

[Journal Home](README.md)

Current Readings:

1. [Spring guide: Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
2. [Baeldung: Comparing repositories](https://www.baeldung.com/spring-data-repositories)

## Reading Notes

### Spring guide: Accessing Data with JPA

There is an empty constructor that is not accessed by the user, so it is set a protected. The other constructor can have all the required fields for an instance that makes sense for the problem domain. The tutorial goes through why JPA is so powerful with the fact that it allows for the database to be accessed so easily. It is important to remember that because the framework being used is Spring MVC, you need to use `./gradlew bootRen` instead of the basic gradlew run command in the terminal.

### Baeldung: Comparing repositories

The Repository interface provides all of the base functionality necessary to manipulate the data in a database. You can use the methods that the Repository has on the interface without defining what they are. Some of the function include:

    - save(): save a Iterable of entities: Here, we can pass multiple objects to save them in a batch.
    - findOne(): get a single entity based on passed primary key value
    - findAll(): get an Iterable of all available entities in a database
    - count(): return the count of total entities in a table
    - delete(): delete an entity based on the passed objects
    - exists(): verify if an entity exists based on the passed primary key value

## Things I want to know more about

I would like to know if there are other industry standard technologies to use on databases. Is JPA preferred over other technologies, or is it similar in performance?

&copy; 2022, NoMichi

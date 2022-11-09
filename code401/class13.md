# Class 13

[Journal Home](README.md)

Current Readings:

1. [Related data in Spring (only read section "3. One-to-Many Relationship")](https://www.baeldung.com/spring-data-rest-relationships)
2. [Baeldung: Spring Integration Testing](https://www.baeldung.com/integration-testing-in-spring)

## Reading Notes

### Related data in Spring (only read section "3. One-to-Many Relationship")

When adding many-to-one and one-to-many relationships use the annotations of `@ManyToOne` and `@JoinColumn(name="library_id")` for the many-to-one relationship and then `OneToMany(mappedBy = "library")` for the one-to-many hook up. The post will be in json. The many-to-one json will contain an array, in this case there would be an array of books in the library call.

In these examples the user is using cURL, or Client URL, to make the data transfers to the database. In our class the instructor used post mate, but you can also add and remove data by setting up proper CRUD setup in the application.

### Baeldung: Spring Integration Testing

This article introduced how to test the GET and POST processes in the Spring MVC testing environment. The addition of data and the pulling of data from the database can be difficult without the tools such as Lightrun. This technology allows for the programer to run these tests without restarting the servers and uses annotations to allow for easy integration into the IDE and project.

## Things I want to know more about

Lightrun reports that it works with Maven, does it also work with Gradle? Or does Gradle have it's own testing suite for CRUD operations?

&copy; 2022, NoMichi

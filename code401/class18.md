# Class 18

[Journal Home](README.md)

Current Readings:

1. [Many to many relationships](https://www.baeldung.com/hibernate-many-to-many)
2. [Security: a humorous overview](https://scholar.harvard.edu/files/mickens/files/thisworldofours.pdf)

## Reading Notes

### Many to many relationships

This articles covers the basic setup for a many-to-many relationship in the spring architecture. The example used for the article is employees and their projects. Many employees can be part of a single project and any give employee can be part of many projects. Thus, there is a joining table used to connect the employee and project `Entity`.

    @ManyToMany(cascade = { CascadeType.ALL })
    @JoinTable(
        name = "Employee_Project", 
        joinColumns = { @JoinColumn(name = "employee_id") }, 
        inverseJoinColumns = { @JoinColumn(name = "project_id") }
    )
    Set<Project> projects = new HashSet<>();

and 

    @ManyToMany(mappedBy = "projects")
    private Set<Employee> employees = new HashSet<>();

### Security: a humorous overview

This was a very colorful article that essentially says that we need to be honest with the level of security that we actually want out of systems. For the average person, we don't need mass amounts of security for everyday products. We just need to keep fairly basic bad actors out of our system. The more sophisticated and relentless bad actors will find a way into the system no matter what.

## Things I want to know more about

How are searches further refined in Spring. For example, all id that are even, or something along those lines.

&copy; 2022, NoMichi

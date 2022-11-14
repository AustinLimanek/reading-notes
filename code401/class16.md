# Class 16

[Journal Home](README.md)

Current Readings:

1. [Spring Security overview](https://spring.io/guides/topicals/spring-security-architecture/)
2. [Spring Authority cheat sheet](https://github.com/codefellows/seattle-java-401d2/blob/master/SpringAuthCheatSheet.md)

## Reading Notes

### Spring Security overview

This article covers the default setting of the Spring security system used for JVM. It discuses how to setup the chain of authorization that is hit before the protected application pages are accessed. In addition, the article discusses authorization mechanisms to distinguish some users from others.

Spring Security relies on interfaces, annotations, and bean to setup the full functionality of the security system. Filters have a very specific order that allows them to work optimally. Furthermore, Bcrypt is the underlying hash algorithm that allow for the password to be ultimately protected from less than savory actors.

### Spring Auth cheat sheet

A nice resource that covers the major components of Spring security for future reference. Although this file is short and does not cover all of the flexibility of the Spring security suite, it dose cover the basics for installation.

## Things I want to know more about

What security systems do large companies use?

&copy; 2022, NoMichi

# Class 14

[Journal Home](README.md)

Current Readings:

1. [Intro to password hashing](https://auth0.com/blog/hashing-passwords-one-way-road-to-security/)
2. [bcrypt overview](https://danboterhoven.medium.com/why-you-should-use-bcrypt-to-hash-passwords-af330100b861)
3. [jBCrypt (the paragraphs and code example at the top of the page)](https://www.mindrot.org/projects/jBCrypt/)

## Reading Notes

### Intro to password hashing

Hashing is an algorithm that takes in characters and maps them into different characters. This process, ideally, is impossible to invert without the key. This should be a one way process for anyone without the key. The key is the inverse of the original algorithm. There are known algorithms that do a real nice job taking care of all the appropriate connections. They provide the hash and also the key to the user and keeps this information secure from external access.

### bcrypt overview

The BCrypt is implied to be the most secure algorithm for password protection. It was invented by Niels Provos and David Mazieres in 1999. This algorithm is very technical, as suggested by the reader. But it apparently the algorithm changes in some way to increase the level of hashing that the plain text experiences.

### jBCrypt (the paragraphs and code example at the top of the page)

The following are the code necessary for using the jBCrypt algorithm in java. This is based on the same algorithm that was described in the second article. 

    String hashed = BCrypt.hashpw(password, BCrypt.gensalt());
    String hashed = BCrypt.hashpw(password, BCrypt.gensalt(12));
    if (BCrypt.checkpw(candidate, hashed))
	    System.out.println("It matches");
    else
	    System.out.println("It does not match");

## Things I want to know more about

I would like to know why systems are still hacked if there are algorithms like this that are reported to be unbreakable?

&copy; 2022, NoMichi

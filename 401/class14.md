# Intro to password hashing

Define the term “hashing”.

  - A more secure way to store a password is to transform it into data that cannot be converted back to the original password. 

Explain to a non-technical friend what a hash function does to a password.

  - hashing is similar so having a puzzle already complete and now it is complety seperated and mixed 

## bcrypt overview

What does it mean to ‘salt’ a password?

- a ‘salt’ adds a very long string of bytes to the password. So even though a hacker might gain access to one-way hashed passwords, they should not be able to guess the ‘salt’ string.

What piece of information would a hacker need to access in order to find the ‘salt’ string for your passwords?

- if a hacker has access to your source code, they will easily be able to find the ‘salt’ string for passwords.

## jBCrypt (the paragraphs and code example at the top of the page)

How does the Blowfish block cipher handle the increased computation speed of new computers?

- modifications designed to raise the cost of off-line password cracking and frustrate fast hardware implementation.

What are the issue with the two most common password hashes for Java (“Java password hash” and “Java password encryption”)?

-  one uses an unsalted hash which allows reverse dictionary lookup of passwords and the other recommends reversible encryption
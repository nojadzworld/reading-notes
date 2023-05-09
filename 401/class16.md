# Spring Security overview

What does it mean to authenticate a user?

- confirming who you are

What does it mean to authorize a user?

- what are you allowed to actually do

What are the three possible outcomes of the `AuthenticationManager`’s `authenticate()` method?

- Return an `Authentication` (normally with `authenticated=true`) if it can verify that the input represents a valid principal.

Throw an `AuthenticationException` if it believes that the input represents an invalid principal.

Return `null` if it cannot decide.

## [Spring Auth cheat sheet](https://github.com/codefellows/seattle-java-401d2/blob/master/SpringAuthCheatSheet.md)


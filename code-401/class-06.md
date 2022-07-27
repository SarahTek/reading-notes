# Readings: Authentication

## Securing Passwords

1. Explain to a non-technical friend how you would safely hash and store a password.

- you can put your password through a hashing algorithm (bcrypt, SHA, etc) to turn plaintext into an unintelligible series of numbers and letters.

2. What is Bcrypt?

- BCrypt is advanced hashing Algorithm that is used to hash and salt passwords securely.

3. Why might you use something like Bcrypt?

- Because Bcrypt allows building a password security platform that can evolve alongside hardware technology to guard against the threats that the future may bring, such as attackers having the computing power to crack passwords twice as fast.

## Basic Auth

1. What is Basic Authentication?

-  Basic access authentication is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request.

2. What properties are necessary in the header of a Basic Auth request?

- Authorization: Basic `<credentials>`, where credentials is the Base64 encoding of `ID and password`joined by a single colon `:`.

3. How are `username:password` in Basic Auth encoded?

- In Basic Authentication `username:password` are encoded in Base64'.

## OWASP auth cheatsheet

1. Define the authentication process to a non-technical recruiter.

- Authentication is the process of verifying that an individual, entity or website is whom it claims to be.

2. How should your error messaging respond (both HTTP and HTML)? Why?

- it response should be generic message without giving any detailed info. this can prevent the creation of a discrepancy factor, allowing an attacker to mount a user enumeration action against the application.

3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

## Resources

- [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)
- [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)
- [OWASP auth cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

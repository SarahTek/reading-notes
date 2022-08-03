# Reading

Intro to JWT

1. What is a JSON Web Token (JWT)?

- JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

2. When should we use JSON Web Tokens?

- When authorizing a user and to securely transmit information between parties.

3. Claims are expected in which structural component of a JWT?

- JSON Web Tokens consist of three parts separated by dots (.), Header, Payload and Signature.

## Are JWTs Secure?

1. If I get a JWT and I can decode the payload, how can we call that secure?

- JWTs can be either signed, encrypted or both. If a token is signed, but not encrypted, everyone can read its contents, but when you don't know the private key, you can't change it. Otherwise, the receiver will notice that the signature won't match anymore.

2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

- The secret key

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

## JWTs Explained

1. Why use JWT?

- JWTs are a good way of securely transmitting information between parties because they can be Digitally signed , which means the information is verified and trusted. you can be sure that the senders are who they say they are.

2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

- compact
  - JWT can be send via URL, POST request, HTTP Header
  - It is Fast Trasmission

- self-contained
  - it contains information about the user
  - it avoids querying the database more than once

3. What are the three components (the structure) of a JWT signature?

- JWT consists of three parts: a Header, Payload, and Signature.


## Resources

- [Intro to JWT](https://jwt.io/introduction/)
- [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)
- [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)
- [npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)
- [What Is JWT and Why Should You Use JWT](https://www.youtube.com/watch?v=7Q17ubqLfaM)

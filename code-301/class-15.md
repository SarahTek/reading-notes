# Authentication

1. What is OAuth?
- OAuth is an authentication protocol that allows you to approve one application interacting with another on your behalf without giving away your password.
2. Give an example of what using OAuth would look like.
- The application or the API asks for authorization from the resource by providing the user’s verified identity as proof.
- telling Facebook that it's OK for ESPN.com to access your profile or post updates to your timeline without having to give ESPN your Facebook password.
3. How does OAuth work? What are the steps that it takes to authenticate the user?
- An application requests authorization on a user's behalf.
- The application obtains a Grant Token.
- The client requests an access token by using the Grant Token.
- The authorization server validates the Grant Token and issues an Access Token and a Refresh Token.
- The client requests the protected resource, authenticating using the Access Token.
- The resource server verifies the Access Token and serves the request.
4. What is OpenID?
-  OpenID is about authentication not authorization. OpenID allows you to use an existing account to sign in to multiple websites, without needing to create new passwords. 
 
 # Authorization and Authentication flows

1. What is the difference between authorization and authentication?
- authentication is the process of verifying who someone is, whereas authorization is the process of verifying what specific applications, files, and data a user has access to.

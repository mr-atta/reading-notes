# Bearer Authorization

## Write the following steps in the correct order:

- Ask the client if they want to sign in via a third party
- Make a request to a third-party API endpoint
- Register your application to get a client_id and client_secret
- Receive authorization code
- Receive access token
- Redirect to a third party authentication endpoint
- Make a request to the access token endpoint

## What can you do with an authorization code? [📁](https://www.oauth.com/oauth2-servers/server-side-apps/authorization-code/)

- The only thing you can do with the authorization code is to make a request to get an access token.
- The authorization code is a temporary code that the client will exchange for an access token. The code itself is obtained from the authorization server where the user gets a chance to see what the information the client is requesting, and approve or deny the request.

## What can you do with an access token? [📁](https://www.oauth.com/oauth2-servers/access-tokens/)

- Access tokens are the thing that applications use to make API requests on behalf of a user.

## What’s a benefit of using OAuth instead of your own basic authentication? [📁](https://developer.okta.com/blog/2017/06/21/what-the-heck-is-oauth)

- It enables apps to obtain limited access (scopes) to a user’s data without giving away a user’s password. It decouples authentication from authorization and supports multiple use cases addressing different device capabilities.

<hr><br>

[VID](https://www.youtube.com/watch?v=926mknSW9Lo)
[📁](https://jwt.io/introduction/)
[📁](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

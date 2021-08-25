# Authorization 🆚 Authentication

> **In simple terms, authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to.** > ![Authorization vs Authentication](https://www.okta.com/sites/default/files/styles/1640w_scaled/public/media/image/2020-10/Authentication_vs_Authorization.png?itok=uBFRCfww)

<br>

## What header(s) are used in authentication and authorization❓ [📁](https://developer.mozilla.org/en-US/docs/Web/HTTP/Authentication)

- The _HTTP_ **WWW-Authenticate** , **Proxy-Authenticate** they are response header defines the authentication method that should be used to gain access to a resource.

- The _HTTP_ **Authorization** , **Proxy-Authorization** they are response header contains the credentials to authenticate a user agent with a server(usually).

<br>

## What is safe to put into a JWT❓[📁](https://auth0.com/blog/a-look-at-the-latest-draft-for-jwt-bcp/)

- The header object contains >> token
- The payload object contains >> all the relevant information,carried by the token

<br>

## How are JWTs validated❓[📁](https://auth0.com/docs/tokens/json-web-tokens/validate-json-web-tokens)

- Third-party libraries >>>> secret key
- Manually implement checks

  1. Check that the JWT is well formed.

     - Verify that the JWT contains three segments, separated by two period ('.') characters.
     - The first segment is the Header, the second is the Payload, and the third is the Signature(base64url encoded).
     - Base64url-decode the Header,verify that it is a valid JSON object.
     - Base64url-decode the Payload,verify that it is a valid JSON object.

  2. Check the signature. (by secret or public key)
  3. Check the standard claims.

  - Token expiration
  - Token issuer

  - If any of these steps fail, then the associated request must be rejected.

- <hr><br>

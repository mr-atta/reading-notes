
![programming ](https://miuc.org/wp-content/uploads/2020/08/6-Reasons-why-you-should-learn-Programming.png)

# OAuth 

 ## What is OAuth?
  > OAuth allows websites and services to share assets among users. It is widely accepted, but be aware of its vulnerabilities.

 ## Give an example of what using OAuth would look like.
  > The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.

 ## How does OAuth work? What are the steps that it takes to authenticate the user?
   * The User Shows Intent
   * The Consumer Gets Permission
   * The User Is Redirected to the Service Provider
   * The User Gives Permission
   * The Consumer Obtains an Access Token
   * The Consumer Accesses the Protected Resource

 ## What is OpenID?
  > is a simple identity layer on top of the OAuth 2.0 protocol. It allows Clients to verify the identity of the End-User based on the authentication performed by an Authorization Server, as well as to obtain basic profile information about the End-User in an interoperable and REST-like manner.


<hr><br><hr>

# Authorization and Authentication flows

 ## What is the difference between authorization and authentication?
   > access to a resource is protected by both authentication and authorization. If you can't prove your identity, you won't be allowed into a resource. And even if you can prove your identity, if you are not authorized for that resource, you will still be denied access.

   > ![Authorization and Authentication](https://miro.medium.com/max/1400/1*kSQKm-yhXuD5yG1r9yGjdw.png)

 ## What is Authorization Code Flow?
   * Regular web apps are server-side apps where the source code is not publicly, they can use the Authorization Code Flow.
   * Which exchanges an Authorization Code for a token. (Your app must be server-side because during this exchange, you must also pass along your application's Client Secret, which must always be kept secure).

 ## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
   * When public clients (e.g., native and single-page applications) request Access Tokens, some additional security concerns are posed that are not mitigated by the Authorization Code Flow alone.

   * The PKCE-enhanced Authorization Code Flow introduces a secret created by the calling application that can be verified by the authorization server; this secret is called the Code Verifier. Additionally, the calling app creates a transform value of the Code Verifier called the Code Challenge and sends this value over HTTPS to retrieve an Authorization Code.

 ## What is Implicit Flow with Form Post?
   > Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.

 ## What is Client Credentials Flow?
   > With machine-to-machine (M2M) applications the system authenticates and authorizes the app rather than a user. For this scenario, typical authentication schemes like username + password or social logins don't make sense. Instead, M2M apps use the Client Credentials Flow (defined in OAuth 2.0 RFC 6749, section 4.4).
  
 ## What is Device Authorization Flow?
   > The Device Authorization Flow contains two different paths; one occurs on the device requesting authorization and the other occurs in a browser. The browser flow path, wherein a device code is bound to the session in the browser, occurs in parallel to part of the device flow path.

   > This avoids a poor user experience for devices that do not have an easy way to enter text

 ## What is Resource Owner Password Flow?
   > requests that users provide credentials (username and password), typically using an interactive form. Because credentials are sent to the backend and can be stored for future use before being exchanged for an Access Token.

   > not recommend it.






 [♥️from](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html) 
 [♥️from](https://www.varonis.com/blog/what-is-oauth/)
 [♥️from](https://openid.net/connect/)


 <hr><br><hr>

 [♥️from](https://auth0.com/docs/flows#authorization-code-flow) 
 [♥️from](https://medium.com/@wathsara/authentications-vs-authorization-f7560d24e0f6)

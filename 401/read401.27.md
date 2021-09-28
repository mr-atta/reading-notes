# `<Login />` and `<Auth />`

<br>
<hr>

## Review, Research, and Discussion

## Why is the Context API useful ❓ [📁](https://www.loginradius.com/blog/async/react-context-api/#:~:text=The%20Context%20API%20is%20a,all%20levels%20of%20your%20application.)

> **The Context API** is a React structure that enables you to exchange unique details and assists in solving prop-drilling from all levels of your application.

## Can a component outside of a provider get its context ❓ [📁](https://stackoverflow.com/questions/49809884/access-react-context-outside-of-render-function)

> With the introduction of react-hooks in `v16.8.0`, you can use context in functional components by making use of useContext hook

## What are some common use cases for using the Context API ❓ [📁](https://flexiple.com/react/provider-pattern-with-react-context-api/)

- Theming — Pass down app theme
- i18n — Pass down translation messages
- Authentication — Pass down current authenticated user

## Describe “Context Hell” ❓ [📁]()

> **React Context hell** is the bad code you get taking advantage of the React Context API.

<hr>
<br>

## ROLE-BASED ACCESS CONTROL (RBAC)

> restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. <br>
> The roles in RBAC refer to the levels of access that employees have to the network.

- you can control what end-users can do at both broad and granular levels.
- You can designate whether the user is an administrator, a specialist user, or an end-user

<br>

### options for user access:

- Primary – the primary contact for a specific account or role.
- Billing – access for one end-user to the billing account.
- Technical – assigned to users that perform technical tasks.
- Administrative – access for users that perform administrative tasks.

<br>

### BENEFITS

1. Reducing administrative work and IT support.
2. Maximizing operational efficiency
3. Improving compliance.

<br>

## react-cookie

> Install: `npm i react-cookie` <br>

> impotr: `const [cookies, setCookie, removeCookie] = useCookies(['cookie-name']);` <br>

- `cookies`

  > Javascript object with all your cookies. The key is the cookie name.

- `setCookie(name, value, [options])`

  > Set a cookie value

  - name (string): cookie name
  - value (string|object): save the value and stringify the object if needed
  - options (object): Support all the cookie options

<!-- ///////////// -->

<!-- ![]() -->

<br>
<hr>
<br>

### Preparation Materials links

[📌 what is role based access control?](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more) <br>

[📌 react-cookies component](https://www.npmjs.com/package/react-cookies) <br>

[📌 react-cookie library](https://www.npmjs.com/package/react-cookie) <br>

<!-- [📌 ]() <br> -->

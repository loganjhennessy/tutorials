# React-Auth0 Tutorial

Following along with [this](
https://auth0.com/blog/react-tutorial-building-and-securing-your-first-app/#Developing-a-Backend-API-with-Node-js-and-Express
)
tutorial published by Auth0.

## Front-end libraries

* `react-router`
* `react-router-dom`
* `axios`
* `auth0-js`

## Back-end libraries

* `express-jwt
* `jwks-rsa`

Commands to get the front end up and running.

```bash
npx create-react-app frontend
cd frontend
npm start
```

For the router...

```
npm i react-router react-router-dom
```

`react-router-native` would be used for mobile for mobile devices rather than
`react-router-dom`.

For AJAX calls...

```
npm i axios
```

For Auth0 on the backend

```
npm i express-jwt jwks-rsa
```

For Auth0 on the frontend

```
npm install auth0-js
```

## Status

Currently able to log in with Auth0. All the way up to the "Adding Features
to Authenticated Users" section, and have already created the `SecuredRoute.js`
file and contents.

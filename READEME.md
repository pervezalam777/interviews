# FAQ

## `Question`: Where do you get the authorization token from 
- Server
- Server that provide authentication mechanism
- There are third party platform like **Auth0** which provide authorization token out of the box.
- [Ref: authentication-token](https://www.fortinet.com/resources/cyberglossary/authentication-token)

## `Question`: Where do you store the auth token
- Depends
- If we are talking about stateless session where authentication token is send to client (mostly as JWT), it can be stored in the following way
  - HTTP only cookies (Preferred)
  - localStorage: for long term use
  - sessionStorage: till the time browser tab is open

## `Question`: Difference between cookies and storage
There are following differences
- Cookies are classical way of storing data while storage is new way of doing so.
- Cookies automatically attached to each request going to server (be it  REST API call, image, js, etc.) while storage data can only be read by client
- Storage is vulnerable to XSS (cross-site scripting) while cookies are vulnerable to CSRF (cross-site request forgery)
- [Learn more on stack over flow](https://stackoverflow.com/questions/3220660/local-storage-vs-cookies)

## `Question`: How to combine 2 interfaces

## `Question`: Are your prod site and server hosted on same domain

## `Question`: If you host site and server on different domain - what are the common issues you get 
## `Question`: If we are in customer support and client is asking for information - then how we keep the client busy or show him something, that will reduce the waiting time. 
## `Question`: What type of queries the client might ask 
## `Question`: How do we fetch details for a client amongst 100 client, each client having more that 100 payment issues. 
## `Question`: How do we implement if an authenticated user is able to access a site. Authorization Question maybe. 
## `Question`: Apart from higher order component - is there a way to set router guards 
## `Question`: What are functional component
## `Question`: How do we consume data in context and provider?
## `Question`: What is React. Context 
## `Question`: What is React.Clone or (React.cloneElement())
- [react-api - clone element](https://reactjs.org/docs/react-api.html#cloneelement)
- [using react clone element function](https://blog.logrocket.com/using-react-cloneelement-function/)
## `Question`: In a functional component, react hooks how do we do component.unmount 
## `Question`: Which version of React are you using 
## `Question`: If there is an array of number, and how to ensure that all results are in then only we can show an object - Promise.all ??
## `Question`: How do browser actually execute an API call 
## `Question`: Do we know what all call go through before the actual API call in a CORS issues - If yes what type of call are those
## `Question`: What security measures do we take to ensure the API request we are sending is not harmful
## `Question`: How can we allow CORS calls. 
# Reading Assignment 12 - Code 301

## Why This Matters

Writing code is an imperfect skill and there will be lots of times that despite writing the perfect code other factors come into play that prevents one server from talking to another. Understanding status codes and what is required for an express server can point a developer to where a problem lies.

## In your own words, describe what each group of status code represents

100’s = Informational
200’s = Various successful status codes
300’s = The source is not in the place it is expected and had to rerequest to the new location
400’s = Request from the client has some type of issue
500’s = Error codes associated with the server

## What is a status code 202?

202 Accepted - Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future.

## What is a status code 308?

308 Permanent Redirect is the right code if the resource will now be available at a new URL and the client should directly access it via the new URL in the future.

## What code would you use if an update didn’t return data to a client?

204 No Content

## What code would you use if a resource used to exist but no longer does?

404 Not Found

## What is the ‘Forbidden’ status code?

403 Forbidden

## Why do we need to pull our MongoDB database string out of our server and put it into our .env?

It is considered sensitive information and we do not want to expose our data to bad actors.

## What is middleware?

A request handler with access to the application's request-response cycle is known as middleware. It's a function that holds the request object, the response object, and the middleware function. Middleware can also send the response to the server before the request.

## What does `app.use(express.json())` do?

The app.use function will use express.json() as middleware function to parse incoming JSON requests and puts the parsed data in the area called specified.

## What does the `/:id` mean in a route?

It allows a parameter to be passed in.

## What is the difference between `PUT` and `PATCH`?

PUT is a method of modifying resources where the client sends data that updates the entire resource. PATCH does a partial update that need to be updated by the client, only that field is updated without modifying the other field.

## How do you make a default value in a schema?

The key is set to `Default` and defaults to in the video example was `Date.now()`.

## What does a 500 error status code mean?

HTTP status code 500 is a generic error response. It means that the server encountered an unexpected condition that prevented it from fulfilling the request.

## What is the difference between a status 200 and a status 201?

200 is the basic status code to tell the client everything went good.

201 is associated with Create operations. This code signals the backend resource creation and comes along with a location header that defines the most specific URL for that newly created resource.

## Things I want to know more about

It was really tough to follow the video. I use closed captioning and the part where it discussed setting a default was very tough to follow. I really don't get it. I would hope that this video's CC gets fixed or a new video is selected because the speaker talks way too fast.

## Sources To Cite

- [Which HTTP Status Code to Use for Every CRUD App](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

- [Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/watch?v=fgTGADljAeg)

- [All You Need to Know About Express JS Middleware](https://www.simplilearn.com/tutorials/express-js-tutorial/about-express-js-middleware#:~:text=A%20request%20handler%20with%20access,the%20server%20before%20the%20request.)

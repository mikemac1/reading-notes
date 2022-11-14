# Reading Assignment 08 - Code 301

## Why This Matters

Understanding the necessity of how a protocol works between a client and a server allows for an application to be supported from multiple enviornments and allows for greater use of the applications.

## What does REST stand for?

Representational State Transfer (REST) is an architectural approach to designing web services. REST is independent of any underlying protocol and is not necessarily tied to HTTP. However, most common REST API implementations use HTTP as the application protocol, and this guide focuses on designing REST APIs for HTTP.

## REST APIs are designed around a ____

REST APIs are designed around **resources**, which are any kind of object, data, or service that can be accessed by the client.

## What is an identifier of a resource? Give an example

A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:
`https://adventure-works.com/orders/1`

## What are the most common HTTP verbs?

 HTTP verbs perform operations on resources and the most common are GET, POST, PUT, PATCH, and DELETE.

## What should the URIs be based on?

When possible, resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource). An example:

## Give an example of a good URI

`https://adventure-works.com/orders` // Good
`https://adventure-works.com/create-order` // Avoid

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

Another factor is that all web requests impose a load on the web server. The more requests, the bigger the load. Therefore, try to avoid "chatty" web APIs that expose a large number of small resources.

## What status code does a successful `GET` request return?

A successful GET method typically returns HTTP status code 200 (OK).

## What status code does an unsuccessful `GET` request return?

If the resource cannot be found, the method should return 404 (Not Found).

## What status code does a successful `POST` request return?

If a POST method creates a new resource, it returns HTTP status code 201 (Created).

## What status code does a successful `DELETE` request return?

If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content), indicating that the process has been successfully handled, but that the response body contains no further information.

## Things I want to know more about

What are the requisite JS components for building a site utilizing an API and are there different templates for developers to use?

## Sources To Cite

- [RESTful web API design](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

- [RegExr](https://regexr.com/)

- [Regex tutorial — A quick cheatsheet by examples](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

- [Regular Expressions](https://regex101.com/)

- [The Movie Database](https://developers.themoviedb.org/3/getting-started/introduction)

- [/businesses/search](https://www.yelp.com/developers/documentation/v3/business_search)

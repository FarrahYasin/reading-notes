

# Readings: Express Rest API

**<span style="color:red">Class-02:Express Rest API💻📗</span>**

 ***why this topic matters as it relates to what you are studying in this module?***
    Express Rest API it is a important concept we must to learn more about it.

_______________________________________________

## Review: ES6 Classes

1. Classes are a template for creating ____.
  Objects.
2. a class declaration be hoisted?
   No
3. How would you describe a constructor and contextual “this” to a non-technical friend?
 In class we can have a special method called constructor, and we called this method when we create new object using the class,
 the constructor is initializes the object's properties,

also we use 'this' when we create a constructor and 'this' is refers to the instance(current instance) of the class
_______________________________________________

## Using Express Routing

1. Within Express, what does routing refer to?
Refer to how will the application respond to user requests for different endpoints or URLs.

2. What is the difference between a route path and a route method?
**route path:**  Determines what type of URL the route will handle
**route method:** Determine what HTTP method the route will respond to, is it GET or DELETE or PUT or POST?.

3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
if we want to pass control to the next middleware or  if we want to pass control to the next route handler in the chain here we can write this parameter to a route handler 'next'. 

if 'next' has been passed to the middleware as a parameter we should call it at the end of function(Middleware Function) to execute the next function after this middleware function
_______________________________________________

## Express Routing

1. What is an Express Router?
It is considered a middleware,and this middleware allows us to create modular to group and organize related tracks.

2. By what mean do we initialize express.Router() in an express server?
const router=express.Router();

3. What do we use route middleware for?

We use route middleware in order to be able to perform certain actions, and in order to create code and reuse it also across different groups of routes.
_______________________________________________

## Reflection

1. What are your learning goals after reading and reviewing the class README?
We considere Express Router a middleware.

_______________________________________________

## Things I want to know more about
I want to learn more about Express😊

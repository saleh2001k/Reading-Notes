# Readings: Express REST API

Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Readings

### Review: ES6 Classes

1. Classes are a template for creating objects.

2. Can a class declaration be hoisted?
   - No, a class declaration is not hoisted. It must be declared before it can be used.

3. How would you describe a constructor and contextual "this" to a non-technical friend?
   - A constructor is a special method within a class that is used to initialize objects created from the class. "this" refers to the current instance of the class and is used to access its properties and methods.

### Using Express Routing

1. Within Express, what does routing refer to?

2. What is the difference between a route path and a route method?
   - A route path defines the URL pattern for a specific route, while a route method specifies the HTTP method (e.g., GET, POST, PUT, DELETE) used to access that route.

3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
   - It is appropriate to add next as a parameter to a route handler when you want to pass control to the next middleware function in the chain. If next is passed to your middleware as a parameter, you must call it at the end of your middleware to proceed to the next function.

### Express Routing

1. What is an Express Router?
   - An Express Router is a middleware that allows you to group route handlers together and define routes for a specific portion of your application.

2. By what mean do we initialize express.Router() in an express server?
   - We initialize express.Router() by assigning it to a variable, usually named router, like this: `const router = express.Router();`.

3. What do we use route middleware for?
   - Route middleware is used to perform additional operations on specific routes. It can be used for tasks such as authentication, input validation, logging, etc.

### Reflection

- What are your learning goals after reading and reviewing the class README?
  - After reading and reviewing the class README, my learning goals are to gain a solid understanding of Express routing and how to create REST APIs using Express. I also want to learn how to implement middleware and handle different route paths and methods effectively.

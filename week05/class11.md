# Event Driven Applications

As soon as Node starts its server, it simply initiates its variables, declares functions and then simply waits for the event to occur. In an event-driven application, there is generally a main loop that listens for events, and then triggers a callback function when one of those events is detected.

![alt](https://www.tutorialspoint.com/nodejs/images/event_loop.jpg)

What native Node.js module allows us to get started with Event Driven Programming?
- The native Node.js module that allows us to get started with Event Driven Programming is called the 'events' module

What is the value of Object Oriented Programming used in tandem with Event Driven Programming?
- Object Oriented Programming (OOP) used in tandem with Event Driven Programming (EDP) brings several benefits. OOP allows us to organize and encapsulate code into reusable objects, which can represent entities or concepts in our application. With EDP, we can define events and event handlers that respond to specific actions or changes in the application state. By combining OOP and EDP, we can create modular, maintainable, and extensible code. Objects can emit events, and event handlers can be associated with specific objects, enabling clear separation of concerns and promoting code reusability.

Consider your knowledge of Event Driven Programming in the Web Browser, now explain to a non-technical friend how Event Driven Programming might be useful on the backend using Node.js.
- Event Driven Programming (EDP) on the backend using Node.js allows us to build highly efficient and scalable applications. Just like in the web browser, where events like button clicks or page loads trigger specific actions, on the backend, we can have events representing various activities or changes in our application. These events can be triggered by different sources, such as user actions, incoming requests, or changes in the system. With EDP, we can define event handlers that listen to these events and perform corresponding actions. This allows us to build responsive, event-based systems that can handle multiple requests concurrently without blocking the execution flow. It helps in organizing complex workflows and enables the development of robust and scalable backend systems.
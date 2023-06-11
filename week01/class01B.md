# Readings: Express, NPM, TDD, CI/CD

Below you will find some reading material, code samples, and additional resources that support today's topic and the upcoming lecture.



## Express

- Explain middleware, answer as though I were a non-technical recruiter.
  - Middleware, in the context of web development and Express, is like a bridge or a layer that connects different parts of a web application together. It helps in handling incoming requests and producing appropriate responses. Think of it as a series of filters that the request passes through, where each filter can perform specific tasks like parsing data, authentication, logging, error handling, and more. Middleware allows developers to add extra functionality and process requests in a structured way, making it easier to build complex web applications.

- Express is the most popular web framework.
  - Express is the most popular web framework for building web applications with Node.js. It provides a set of tools and features that simplify the process of handling HTTP requests, routing, and creating APIs. Express is widely used due to its simplicity, flexibility, and extensive community support.

- Express is "unopinionated." What does that mean?
  - When we say that Express is "unopinionated," it means that the framework does not impose a specific structure or way of doing things on the developers. Express provides a minimalistic foundation for building web applications and leaves the choices regarding the application's architecture, organization, and additional features to the developers. This allows developers to have more freedom and control over their code and make decisions that best fit their project's requirements.

## NPM

- What is a module and why is modularity useful to us as developers?
  - A module is a reusable and self-contained piece of code that encapsulates related functionality. It can include variables, functions, classes, and more. Modularity is useful to developers because it promotes code organization, reusability, and maintainability. By breaking down the code into smaller modules, developers can manage complexity, improve code readability, and easily reuse or replace modules as needed. It also allows for better collaboration among developers, as modules can be developed and tested independently.

- What is NPM?
  - NPM (Node Package Manager) is a package manager for Node.js. It is a tool that allows developers to discover, install, manage, and share reusable code packages (called "packages" or "libraries") written in JavaScript. NPM simplifies the process of incorporating external code into a project, saving developers time and effort by providing a vast ecosystem of pre-built packages that can be easily integrated into their applications.

- What version of npm are you running on your machine?
  - To check the version of NPM installed on your machine, you can open your command-line interface (such as Terminal or Command Prompt) and type the following command: `npm -v`. It will display the version number of NPM installed on your machine.

- What command would you type to install a library/package called 'jshint' into your node project?
  - To install the 'jshint' package into your Node project, you can open your command-line interface and navigate to your project's directory. Then, you can type the following command: `npm install jshint`. This command will download and install the 'jshint' package, making it available for use within your project.

## TDD

- What is TDD?
  - TDD stands for Test-Driven Development. It is a software development approach where developers write tests before writing the actual code. The development process typically involves three steps: writing a failing test, writing the minimum code to pass the test, and then refactoring the code while ensuring that all tests still pass. TDD focuses on the idea of creating a comprehensive suite of tests to drive the development process and guide the design of the software.

- Explain why tests are important. Please explain as though I were your non-technical elder.
  - Tests are important because they help ensure that the software we build works correctly and reliably. They act as a safety net, catching errors and bugs before they reach the end-users. For example, think of tests like a series of quality checks that verify whether the code performs as expected. By running tests, we can catch mistakes early on, which saves time, money, and effort in the long run. Tests also make it easier to understand and modify the codebase, as they provide documentation and examples of how different parts of the code should behave.

- What are three expected benefits of testing?
  - Increased confidence: Tests provide reassurance that the code is working as intended, giving developers and stakeholders confidence in the software's reliability.
  - Bug detection: Tests help identify bugs and errors in the code, allowing developers to fix them before they cause issues for end-users.
  - Code maintainability: Tests act as documentation, helping developers understand the expected behavior of the code. They make it easier to modify and refactor the codebase without introducing unintended side effects.

- Name at least two individual pitfalls and at least two team pitfalls commonly encountered while writing tests.
  - Individual pitfalls:
    - Overcomplicating tests: Writing overly complex tests can lead to difficulties in understanding, maintaining, and debugging them.
    - Neglecting edge cases: Failing to consider and test edge cases can result in unhandled scenarios, leading to bugs and unexpected behavior.

  - Team pitfalls:
    - Lack of collaboration: Ineffective communication and coordination among team members can lead to duplicated efforts, inconsistent testing approaches, and inefficient test coverage.
    - Slow test execution: If tests take a long time to run, it can slow down the development process and reduce productivity. This can discourage running tests frequently, leading to a decrease in code quality.

## CI/CD

- What are three benefits of Continuous Integration?
  - Early bug detection: Continuous Integration allows for the automatic building and testing of code changes as they are committed, catching bugs and issues early in the development cycle.
  - Faster feedback loop: Developers receive immediate feedback on the quality and compatibility of their code changes, enabling them to make adjustments promptly.
  - Reduced integration problems: By integrating changes frequently, CI helps identify conflicts or compatibility issues between different parts of the codebase, making it easier to resolve them early on.

- What is the difference between Continuous Delivery and Continuous Deployment?
  - Continuous Delivery (CD): Continuous Delivery is a software development practice where code changes are automatically built, tested, and prepared for release. However, the actual deployment to the production environment is typically done manually by the development team or stakeholders.

  - Continuous Deployment (CD): Continuous Deployment goes a step further than Continuous Delivery. In Continuous Deployment, code changes that pass all the necessary tests and checks are automatically deployed to the production environment without any manual intervention. This allows for a faster and more frequent release of new features and bug fixes.

- Explain how GitHub fits into this process, assuming the listener comes from a non-technical background.
  - GitHub is a web-based platform that facilitates collaborative software development using version control. It allows developers to store their code repositories, track changes made to the code over time, and collaborate with other team members. In the context of Continuous Integration and Continuous Deployment, GitHub integrates with CI/CD tools to automate the building, testing, and deployment processes. Developers can configure workflows on GitHub that trigger these processes whenever changes are pushed to the code repository. This integration helps streamline the development and release cycle by automating various tasks and ensuring that changes are thoroughly tested before being deployed to production.

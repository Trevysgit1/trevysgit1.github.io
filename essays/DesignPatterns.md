---
layout: essay
type: essay
title: "Why Design Patterns?"
# All dates must be YYYY-MM-DD format!
date: 2026/07/30
published: true
labels:
  - ICS 314
  - Design Patterns
---

## What are Design Patterns?
Design patterns are reusable templates and solutions that can be used in common software engineering problems. They are not solutions that solve a typical software engineering problem like adding features or implementing an algorithm. Instead, they use known methods and good practices for structuring code that can be used to solve common software engineering problems. Following design patterns allow you to build code that is easier to develop and build on in the future, modify, and reuse. 

The purpose of design patterns is to allow developers to reuse solutions to recurring software engineering problems. They allow you to maintain consistency across projects even if the purposes and goals of the projects are different. Similar to coding standards, utilizing design patterns allows developers to improve the structure of their code, make it easier to debug, and support collaboration by allowing the reuse of code.

## Examples of Design Patterns
Design patterns refer to the reusable blueprints used to solve recurring software engineering problems, some of the common and useful blueprints include Singleton, MVC, Observer, Factory, Publish-Subscribe, Prototype, Front Controller. Singleton says that there should only be one instance of a class where you use this one instance globally instead of making copies in local files. MVC divides the structure of a code into three components the model, view, and controller. The model is what is on the backend which stores and manages all of the data, the view if the frontend which is everything that the user sees and interacts with, the controller is what accepts the users inputs and processes them from the view to send to the model. The factory design pattern looks at how objects are created and says that a method should be used to create an object. Publish-Subscribe says that the publisher provide information or a message to a source without knowing or caring about who will read them and the subscribers can find information they are interested in without even knowing who published it. The prototype design pattern allows you to reuse code without worrying about the dependencies of the code that were in the previous implementations. The Front Controller pattern handles every request instead of having multiple gateways users are able to login at this allows the developer to process every request in one place. 

In my final project Club Compass there were multiple design patterns used. One of the patterns is the Singleton, an example of it is the database that is created in the seed file, you don't want to create multiple unnecessary databases, instead we created one database and reused it for all of the clubs and records. We also implemented the MVC design pattern, the model represents the schema.prisma where the database and tables are defined, the view is the page.tsx where the frontend view that the user sees, the controller is the route.ts which controls the connection between the page.tsx and the schema.prisma. The Front Controller pattern is also utilized in the auth.ts which handles the authentication, sign in, and sign out where every request is processed through this one gateway instead of having multiple gateways for each separate request. 

## Conclusion
Design patterns provide developers with reusable solutions for organizing and improving structure of code. In the Club Compass project these design patterns like Simpleton, MVC, and Front Controller were used to separate responsibilities between the frontend and backend. Design patterns are important to use even if you don't realize you are using it because they allow you to save time in the long run by making it easier to modify, reuse, and build on your current code by structuring it using design patterns.

# Ember Diagnostic

What are three advantages of using Ember?

```sh
1. The Ember CLI gives developers a set of tools that save them the time and energy of having to organize their code into modules, create mock servers for the front end and setting up build tools.
2. The use of handlebars templating reduces the amount of overall written code and builds the HTML document dynamically.
3. Ember favors following naming conventions which makes it easy to follow and read.
```

What is the templating system used in Ember? How it is related to
handlebars?

```sh
There is a handlebars templating engine that reduces the amount of code needed in most applications. It depends on straight text manipulation and builds the HTML document dynamically
```

Name and describe at least two layers of an Ember application:

```sh
The Object Model changes javascript objects with computed priorities, inheritance, mixins and other useful functions. object properties are automatically obounds, which gives us a lot of power and flexibility.

```

How does a component differ from an Ember template?

```sh
An ember component is a view that is completely isolated.
A template is compiled automatically and available everywhere.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
A framework is opinionated when it locks or guides you into their way of doing things.
Ember is opinionated because it insists on developers following its rules and standards.
It forces developers to decouple data manipulation from its side-effects.
It values convention over configuration.
```

In Ember what is a route's job (please list three)?

```sh
1. A routes job is match a URL to a controller action. The controllers job is to load data and render a template.
2. Data operations go in the route, because in Ember, the owner of a certain object is the only one allowed to manipulate it.
Data goes down and actions  go up - routes pass model data down to components, and have their actions called by components.
3.The router also sets up the application state.
```

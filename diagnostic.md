# Ember Diagnostic

What are three advantages of using Ember?

```sh
1.less AJAX
2.uses states of the webpage
3.uses the URL as the routing
```

What is the templating system used in Ember? How it is related to
handlebars?

```sh
It uses handlebars and the bacon brackets.  it binds the html to the computed properties
```

Name and describe at least two layers of an Ember application:

```sh
1. The view layer; that is the one that is currently on the screen.
2. The routes layer; this is where the UI finds data via pathes outlined in the routes.
```

How does a component differ from an Ember template?

```sh
A component is a custom HTML tag. Behavior is implemented using JavaScript and its appearance is defined using HTMLBars templates. Components "own" their data. They can also be nested and can communicate with their parent components through actions.
On the other hand Templates are used to build the application's HTML and are written with the HTMLBars
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
This means that the framework makes assumptions about software development best practices and your application’s architecture.  Ember follows Convention over Configuration (CoC), and the Don't Repeat Yourself (DRY) principle. It has been described as a highly opinionated framework built to be very flexible
```

In Ember what is a route's job (please list three)?

```sh
It can render a template.
It can load a model that is then available to the template.
It can redirect to a new route, such as if the user isn't allowed to visit that part of the app.
It can handle actions that involve changing a model or transitioning to a new route.

```

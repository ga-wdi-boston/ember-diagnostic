# Ember Diagnostic

What are three advantages of using Ember?

```md
Ember supports saving states through URLs, and is designed in part around that principle
Ember reduces the need to write tons of jQuery and ajax calls.
Ember saves time and provides a built in structure for a project.
```

What is the templating system used in Ember? How it is related to
handlebars?

```md
Ember uses HTMLbars, which is essentially the same as handlebars except that it directly creates DOM elements rather than just html strings
```

Name and describe at least two layers of an Ember application:

```md
The router is the layer which determines what state the application should be in at any given point.
The model layer interacts with the back end to provide the data required by the application
```

How does a component differ from an Ember template?

```md
An Ember template is simply the HTML markup for a resource, whereas the component encompasses all the actions and data for that resource as well as the template
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```md
An opinionated framework is one which favors convention over configuration and in some sense forces a particular structure onto a project. Ember is most certainly opinionated, because it enforces certain naimg conventions, application structure philosophy (aka an MVVM framework), and interactions between components.
```

In Ember what is a route's job (please list three)?

```md
A route's job is to 1) provide URL support so that users can easily return to a given application state, 2) tell the application which templates to display, and 3) tell the application which methods, if any, to invoke to provide data/content to the template.
```

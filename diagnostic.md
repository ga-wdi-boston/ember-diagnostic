# Ember Diagnostic

What are three advantages of using Ember?

```sh
- give client-side application a lot of structure right out of the box
- give app a lot of front-end best practices, standards, and conventions
- build a state-dependent UI in a proven, standardized way
```

What is the templating system used in Ember? How it is related to
handlebars?

```sh
Ember uses a Handlebars templating library. Handlebars templates are just like
regular HTML or Handlebars, but also give you the ability to embed expressions
that change what is displayed.
```

Name and describe at least two layers of an Ember application:

```sh
-  Routing: links app state to the UI via URLs and their associated routes
-  Models: where state lives, each route has a model
```

How does a component differ from an Ember template?

```sh
Templates: how page's HTML gets built; Ember uses Handlebars templating language
Components: HTML tags with custom behavior (via JavaScript) and appearance (via templates)

Thus components are subset of templates, and are reusable chunks of code that can
help simplify your templates.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
If a framework is opinionated, it lock or guides you into their way of doing things.
Ember is opinionated because it will disregard your code if you do not follow
its conventions, which forces you to adhere to several standards and best
practices (which is usually a good thing but can make debugging/finding errors
somewhat difficult).
```

In Ember what is a route's job (please list three)?

```sh
- parses information contained in the URL, such as an ID or a query string
- links the Router to a particular Component/Template (among other things)
- loads the UI element's data via a method called model
```

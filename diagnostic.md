# Ember Diagnostic

What are three advantages of using Ember?

```sh
1) Convention over configuration
2) Client-Side Rendering
3) URL-Support
```

What is the templating system used in Ember? How it is related to
handlebars?

```sh
Handlebars is a templating library to build semantic templates.
Ember uses handlebars but extends with additional features / helpers to
give more functionality.
```

Name and describe at least two layers of an Ember application:

```sh
The essentials part of Ember 2 applications are the Object Model, Routing,
 +Models, Services, and Components.
```

How does a component differ from an Ember template?

```sh
The template is created via handlebars and includes HTML plus code. This
will be compiled by the application at run-time. Components are decoupled
and reusable pieces of html/code - an example might be a blog article. The
component can be reused again for each post (with different data).
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
An opinion framework makes decisions for the users on how certain things
should be setup and performed. Ember is very opinionated - an example
would be how it handles asychronous bheavior. An example of an unopinionated
library would be backbone.js.
```

In Ember what is a route's job (please list three)?

```sh
1) It can render a template.
2) It can load a model that is then available to the template.
3) It can redirect to a new route, such as if the user isn't allowed to visit that part of the app.
```

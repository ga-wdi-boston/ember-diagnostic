# Ember Diagnostic

What are three advantages of using Ember?

```sh
Ember includes powerful tools like the ember inspector and the auto-refresh server

Ember uses a front end routing system to display view states with corresponding URLs, allowing users to navigate with the back and forward buttons in the browser.

Ember uses a robust templating system where you can model your data in chunks as components to be used in different view states depending on where in the app your user is.
```

What is the templating system used in Ember? How it is related to
handlebars?

```sh
Ember\'s templating system is very similar to the handlebars we have worked with previously. You can use helpers to do things like loop through an array of objects and access properties on the objects to be displayed by their key name. You can break the templates down into components and then include these components in however many templates you want depening on the view state of the user.
```

Name at least two layers of an Ember application (1.0 or 2.0):

```sh
Models, Testing, Router, Routes, Templates, Components
```

How does a component differ from an Ember template?

```sh
Components are isolated views that aren\'t aware of the context outside of them. They can be included as a part of one or many templates.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
Ember is an opinionated framework. If you use it to generate things for you it will automatically inject best practices into the file system and naming conventions. This takes some of the guesswork out for you and it also enables people to jump into an Ember app they did not write while still being able to find their way around.
```

In Ember what is a route's job (please list three)?

```sh
The route maps the URL to the specific route handlers which can then render a template, load a model to make available to the template, redirect to a new route if necessary, etc.
```

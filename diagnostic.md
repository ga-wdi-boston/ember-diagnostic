# Ember Diagnostic

What are three advantages of using Ember?

```sh
- Ember allows you to easily make use of different URLs on your SPA through the
implementation of front end routing.

- The services portion of ember will make it so you dont have to write ajax
calls nearly as mucha as you would ahve to without it.

- Ember increases the responsiveness of a SPA by loading data to the page quicker
than is possible without it.
```

What is the templating system used in Ember?

```sh
HTMLbars, a variation of handlebars, is the templating system used in ember
```

When we code we'll typically start with the Ember Template, but Ember has a
project generator, what is the command to generate a new ember application?

```sh
'ember new my-new-app' will generate a new ember project with the name 'my-new-app'
```

Name at least two parts of an Ember application (1.0 or 2.0):

```sh
- router
- model
- components
- services
```

How does a component differ from an Ember template?

```sh
A component is a custom html tag that you build. A component is made up of a
template built using HTMLbars to determine its appearance and javascript to
determine how it will act.
```

Is Ember opinionated?

```sh
Yes, Ember expects you to name things particular ways and to put files in
certain places. It assumes you follow best practices in these areas.
```

In Ember what is a route's job (please list three)?

```sh
Routes look at the URL and then take certain actions depending on the current
state or the URL.

Routes call the model hook

Routes then use data from the model and pass it to the controller which will display
it by making use of a template.
```

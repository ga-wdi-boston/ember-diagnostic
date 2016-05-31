# Ember Diagnostic

What are three advantages of using Ember?

```sh
- URLs are maintained - so the internet doesnt break from hastags
- Everything is rendered from models, keeping code very DRY
- Good error messaging, since Ember has opinions and expects you to follow certain conventions
```

What is the templating system used in Ember?

```sh
All pages are rendered with HTML templates that are assembled upon the client updating a view state, rather than all view states explcitly typed out in full HTML.  Instead of handlebars.js, HTMLbars is used for all HTML.
```

When we code we'll typically start with the Ember Template, but Ember has a
project generator, what is the command to generate a new ember application?

```sh
ember new <my-new-app>
```

Name at least two parts of an Ember application (1.0 or 2.0):

```sh
- Components
- Routes
```

How does a component differ from an Ember template?

```sh
A component allows you to define a custom element to use in HTMLbars templates, instead of having to re-use the same chunk of vanilla HTML each time you want to display something in a certain way.  A component is used in an ember template.
```

Is Ember opinionated?

```sh
Yes - it expects you to follow certain conventions that developers in general and the develiopers of Ember in particular have ecided are important and worthwhile.
```

In Ember what is a route's job (please list three)?

```sh
- To tell which model is rendering a view
- To know what URL to display to the client
- To handle actions that can change a model or transition to a new route
```

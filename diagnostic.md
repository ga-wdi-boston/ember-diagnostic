# Ember Diagnostic

What are three advantages of using Ember?

```sh
Using URL and routing. Routing allows us to switch between different view states. Ember is a stable framework.
```

What is the templating system used in Ember? How it is related to
handlebars?

```sh
Template in Ember uses HTMLBars. It is like HTML but it gives us ability to change the content that is shown on the page. Each template has its own controller where are properties that will be rendered on the page.
```

Name at least two layers of an Ember application (1.0 or 2.0):

```sh
Templates, routes.
```

How does a component differ from an Ember template?

```sh
A component can appear on any page, and each component has its own template. Template renders the data from the model.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
Opinionated framework means that is intuative, model that holds data is singular, controllers that holds the actions is plural like in Rails, Ember is opinionated too.
```

In Ember what is a route's job (please list three)?

```sh
Route's job is to render the view state by accessing model property in the controller that accessing controller property in the template, and then template will render data from the model.

Each route has its own job, for example:
- it redirects the URL
- it updates controller so controller shows a specific model (asked by the route)
- it changes the template depending on the URL.
```

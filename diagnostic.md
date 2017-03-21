# Ember Diagnostic

What are three advantages of using Ember?

```sh
Less Ajax, stability, responsive, fast - stores some server data to access fast the client request.
```

What is the templating system used in Ember? How it is related to
handlebars?

```sh
Ember View - the files end with .hbs
It has similar syntax as handlebars - it is also dynamic and needs javaScript.
To create a new template file under template/ - I can run $ ember generate template
nameOffile
```

Name and describe at least two layers of an Ember application:

```sh
Templates, routes, views, controllers, models, components.

An Ember app uses the routing layer to resolve, based on the URL, a particular model which is then handed over to a component for display and interaction. A service may be used to retrieve models.

Components consist of two parts: a Javascript component file (that defines behavior) and its accompanying Handlebars template.
```

How does a component differ from an Ember template?

```sh
Often times, my components will just encapsulate certain snippets of Handlebars templates that I find yourself using over and over.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
# your answer here
```

In Ember what is a route's job (please list three)?

```sh
To let our application know what URL this View corresponds to, we need to add it to the Ember Router.

Defining a new route in the Router will create all of the other objects for me, and as a result, the only time when I actually create any of those objects (by making your own files) is when you want to override the defaults.

It lets me move very quickly when developing an Ember application.
```

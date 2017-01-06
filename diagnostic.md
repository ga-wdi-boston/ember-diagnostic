# Ember Diagnostic

What are three advantages of using Ember?

```sh
1. Organizing code into modules.
2. Setting up build tools.
3. Client side rendering.
```

What is the templating system used in Ember? How it is related to
handlebars?

```sh
The templating system in Ember is used by the router to display relevant information to the user in the view-state. Each template was written in Handlebars, and could access and manipulate properties in the View. In-built Handlebars helpers such as {{#if}} and {{#each}} were also available.
```

Name at least two layers of an Ember application (1.0 or 2.0):

```sh
Data layer, model layer.
```

How does a component differ from an Ember template?

```sh
A component can be invoked from within a template and it does not have access to the entire scope of the route, its scope is explicitly defined at the locaiton where the component is invoked.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
An opinionated framework is a framwork that locks you into a certain way of doing things. Ember is an opinionated framework. An example of this is the strict naming conventions for files. Essentially there is 'one way (i.e. the right way according to that framework)' to do things.
```

In Ember what is a route's job (please list three)?

```sh
1. Parsing info contained in the URL
2. Linking the router to a particular component / templates
3. Loading the UI elements data via a method called model.
```

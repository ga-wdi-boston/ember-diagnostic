# Ember Diagnostic

What are three advantages of using Ember?

```sh
1) Ember is very modular, meaning ember applications are broken down into many
small parts, keeping code seperated.
2) Conventionality; ember applications can be created quicker and more
efficiently with command-line actions like 'generate'.
3) Ember allows for 'computed properties', which allow functions to be declared
as properties of objects. Very practical if you know how to write them and
implement them
```

What is the templating system used in Ember? How it is related to
handlebars?

```sh
HTML content for a route or component of the page is proided by the ember
templating system via handlebars.
```

Name and describe at least two layers of an Ember application:

```sh
The ember model.js layer takes data pulled from the applications central data store.
The model then defines resources from a routes store property.

The ember adapter handles the details of different reource data storage systems.
```

How does a component differ from an Ember template?

```sh
Components represent all UI elements, are modular, and reusable, while templates
are associated with one specific use.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
Opinionated frameworks generally have higher levels of data abstraction. Ember, at
least compared to other JS frameworks, falls into this catagory.
```

In Ember what is a route's job (please list three)?

```sh
The routes job is to (1)parse info contained in a url(such as an id), (2) Link the router to a particular component/template, and (3) Load ui elements data via a method called model.
```

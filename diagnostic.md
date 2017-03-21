# Ember Diagnostic

What are three advantages of using Ember?

```md
- Routing: Ember puts URLs at the core of it's design philospohy and provides and robust framework for front-end routing.
- AJAX: Ember keeps a copy of backend resouces and handles the heavy lifting of keeping client and server resources in-sync.
- Responsivness: Ember abstracts away the problems of having to update the view-state when it's underlying data changes.
```

What is the templating system used in Ember? How it is related to
handlebars?

```md
The templating system in Ember is called HTMLBars. It is based off of handlebars and follows a similar syntactical structure. Unlike Handlebars, it is built for integration with Ember and can be automatically updated when it's underlying model changes.
```

Name and describe at least two layers of an Ember application:

```md
Route: A map of all the URLs possible in your application and their corresponding templates.
Model: Specifies the source and state of underlying data for a given route.
```

How does a component differ from an Ember template?

```md
A component is a small bit of code not unlike a handlebars partial. Components are used to render frequently rendered blocks of code. For instance a thumbnail.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```md
An opinionated framework is one with standard conventions and a governing philospohy about how things should be done. Ember is an opinionated framework. Ember apps have a similar structure and it often relies on convential naming conventions to work properly.
```

In Ember what is a route's job (please list three)?

```md
A route specifies which model a particular URL should interact with when a view is loaded.
```

# Ember Diagnostic

What are three advantages of using Ember?

```
Ember is uniform across websites, meaning that one looks similar to another and is easy
to look at and understand, even if you didn't write the code.  It also has a big following on the web,
great docs and great support by the people that wrote it.
```

What is the templating system used in Ember? How it is related to
handlebars?

```
The templating system controls your view layers in Ember.  You have your root view,
which is just your app html, and then you have views for each of the routes you've
implemented.  It is handlebars, but it also has it's own features that come with Ember.
```

Name at least two layers of an Ember application (1.0 or 2.0):

```
Routes, which determine the view layer, and components, which are basically
chunks of code that can be used as many times as you need in varying locations throughout your website.
```

How does a component differ from an Ember template?

```
An Ember template should be used for a specific view state (displaying specific information after a specific action), but components are pieces of code that can be utalized in several different places to do the same thing.  General rule is that if you're using a component only once, it probably shouldn't be a component.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```
Opinonated framework is a framework that locks in the way it needs you to do something.  In this
way it allows for less mistakes or deviation from what it is intended to do.  Ember is very opinonated.
That is exactly why it was made, to make it easier to build front ends and reduce mistakes.  Ember has specific ways that it names files and paths and speciic ways that it looks for those files on actions.
```

In Ember what is a route's job (please list three)?

```
The routes job is to parse information in the url and link the url to a template - it then loads data using the model.
```

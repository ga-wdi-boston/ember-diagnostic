# Ember Diagnostic

What are three advantages of using Ember?

```sh
It is an extention of javascript and allows developers to code the front and back end using javascript.  The development tools are also an advantage (ie ember inspector).  It provides more information to debug and develop.  The use of urls for different view-states.  This allows users to use the back button and to be able to see a view state more easily.
```

What is the templating system used in Ember? How it is related to
handlebars?

```sh
The template system in Ember is similar to handlebars in terms of syntax.  For instance, both use "vacant brackets" to indicate where data from the database should be inserted.  They differ in that Ember provides the developer to work with the controller and view (in addition to the template).  Meanwhile, handlebars can only be used with the template view.
```

Name and describe at least two layers of an Ember application:

```sh
The view layers responds to user interaction (e.g. clicking) and are created using templates.  Ember enables views and templates to work together.

In Ember, the model layer includes the data that the application is using (i.e. showing to the user).  Models are objects and data is not lost when an applicatin is closed.
```

How does a component differ from an Ember template?

```sh
Components allow a developer to define his own app-specific HTML and use this with JavaScript Code.  Technically, an ember component is a subclass of a template, but they are kept isolated.  This allows context to be separated and prevents scoping issues.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
An opinionated framework is one that makes assumptions on best practices of the application architecture.  Ember can be thought of as an opinionated framework because of its asynchronous behavior.
```

In Ember what is a route's job (please list three)?

```sh
The route defines which which controller to point to, which url to display and which template to show.
```

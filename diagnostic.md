# Ember Diagnostic

What are three advantages of using Ember?

```sh
It allows you to use much less code to achieve the same functionality as Jquery.
You can get a functioning app running much quicker than without.
You can make fewer requests to the backend and still have the same functionality.
You can save and share the state of an app with different URLs.
```

What is the templating system used in Ember? How it is related to
handlebars?

```sh
Ember uses handlebars for its template files.  It allows us to reuse the same
piece of HTML with variables to reduce code.  Also makes HTML so you dont have
to scroll through lines and lines of HTML.
```

Name and describe at least two layers of an Ember application:

```sh
The view layer is one of the most important concepts in Ember, because Ember was
designed to make displaying different views much simpler.  Each view has its
own URL which allows sharing of the state of an app at any given point a breeze.

The model is another important layer.  The model is the object that gets
rendered by the templates using handlebars to subsitute for each instance
of the model.
```

How does a component differ from an Ember template?

```sh
Components define custom HTML tags and the content in them to be used as a
modular entity.  A template can be one piece of a component, or it can be
separate and used to render some static data.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
An opinionated framework is one that requires that things be done a certain way
or it breaks.  Ember is definitely opinionated.  When it works, it works really
well, but when it doesnt work it can be hard to diagnose the issue because each
part of the app has to be exactly correct or it wont work at all.
```

In Ember what is a route's job (please list three)?

```sh
A route determines which view will be on the screen.
A route determines what the URL of that view will be.
A route determines which format of which path will lead where.
```

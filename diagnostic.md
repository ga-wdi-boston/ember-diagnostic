# Ember Diagnostic

What are three advantages of using Ember?

```sh
Ember and other front end frameworks allow us to generate discrete pieces of a
website, making them much easier to write than worrying about writing the HTML
in one place and the CSS somewhere else entirely.

Ember in particular allows us to create custom sub-urls for our websites which
allows for easy navigation (and even makes it easier for us to test if our code
is working the way we think it is!)

Ember uses familiar frameworks to make its pages.  The overall structure is
reminiscent of Rails, and the templating engine itself is very similar to
handlebars.
```

What is the templating system used in Ember? How it is related to
handlebars?

```sh
Ember uses HTML bars, which is handlebars that, according to this source,
generates DOM objects for insertion rather than just passing the browser a pure
string.  Source here: https://colintoh.com/blog/htmlbars (I am planning on
reading more about this if there is time post-diagnostic)
```

Name and describe at least two layers of an Ember application:

```sh
Router: the router fetches the templates for the specified URL
Template: The templates are the HTMLbars that put the THINGS on the SCREEN.
(sorry for bad phrasing, could not come up with something better.)
```

How does a component differ from an Ember template?

```sh
I am struggling with this one, and the documentation about what a component is
is pretty unclear.  I think a component is a separate sub-url that does not link
share the main page of the app?  I really am not sure.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
An opinionated framework wants users to follow certain patterns that it lays out.
Ember is extremely opinionated - it generates files with very specific names, to
say nothing of the very specific ways it has of calling and manipulating Ember
objects.  I found the below stack overflow helpful.

http://stackoverflow.com/questions/802050/what-is-opinionated-software
```

In Ember what is a route\'s job (please list three)?

```sh
Recognize a specified URL
Load the template of said URL
[from the docs] it can redirect to a new route if the user is not allowed to
access a certain part of the site.
```

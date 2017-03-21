# Ember Diagnostic

What are three advantages of using Ember?

```sh
Less ajax, more resposiveness(as in how quickly a page loads information) And
having more control over the url. Previous to ember we could not have control
over history, using the refresh button or the back button. With ember we can now
make use of these tools.
```

What is the templating system used in Ember? How it is related to
handlebars?

```sh
HTMLbars is a way of USING handlebars for more effective output. With handlebars
you have one template which handles an action, but that action only talks to the
html file. With html bars there are several templates, that can all talk to each
other and the models and then that information gets swept down to the index.html
file which renders said templates.
```

Name and describe at least two layers of an Ember application:

```sh
Model

view

Controller
```

How does a component differ from an Ember template?

```sh
A componenent, even though it is in a templating file, only holds that one
componenent/element. This then allows that component to be used elsewhere
in other templates
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
An opinionated framework is a framework which has a set of rules/expectations
for how things are done. Ember is opinionated in the way that it expects all then
naming to be done in a very specific fashion. camelCase vs kebab case. Ember is
very specific about where to use these different naming conventions. Components
must alwass be in kebab. And nowhere else and all the names need to line up from
the routes to the model to the controller, this was not the case in rails which
was another opinionated framework.

```
In Ember what is a route's job (please list three)?

```sh
The job of the route in ember is to define where the model is comunicating
the data that it holds to, you can define the path, and the location type. When
generating routes with generator from the command lines, these get set up for us
```

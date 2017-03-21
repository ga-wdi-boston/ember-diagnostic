# Ember Diagnostic

What are three advantages of using Ember?

```sh
1. Unlike some front-end javascript frameworks, URL routing is central to Ember.  URL routes are used to transition state, fetch data, and in some cases, replicate browser history.  Because of this, ember applications can be said to more fully embrace the web.
2. Ember is a mature framework with a lot of tooling supporting it.  The Ember CLI, for example, allows developers to quickly scaffold new applications and add new features to existing applictions.
3. A developer who understands ember can more easily begin working on an existing application because of the frameworks adherence to convention.
```

What is the templating system used in Ember? How it is related to
handlebars?

```md
Ember templates are simply handlebars files.  The only difference between normal handlebars and ember handlebars (and I believe this is not exposed to framework users in any meaningful way) is that ember's implementation allows  for access to Ember Object properties.
```

Name and describe at least two layers of an Ember application:

```sh
Routing Layer
Model Layer
```

How does a component differ from an Ember template?

```sh
Components in ember are an implmentation of the web component standard.  They render to custom-named HTML elements in the DOM.  Conceptually components differ from templates in that components should be stand-alone, self contained units not tied to a given route or model.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```sh
An opinionated framework favors convention over configuration and must be implmented in specific ways. Ember certainly fits this description.  Ember apps require compliant file structuring and entity and file naming,for example.

```

In Ember what is a route's job (please list three)?

```sh
1.Routes load data.
2.Routes maintain application state.
3.Routes load templates.
```

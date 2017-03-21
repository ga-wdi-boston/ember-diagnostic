# Ember Diagnostic

What are three advantages of using Ember?

```md
- You can use the URLs to get to different views, which is super convenient in
a single-page application
- We can store data locally before waiting for the server to respond! So if
you're playing a game or something but you're offline, the server will update
with the locally saved data whenever you get reconnected
- It allows developers to separate concerns in an organized and efficient fashion.
```

What is the templating system used in Ember? How it is related to
handlebars?

```md
You use handlebars in your Ember template, and this template will reference different
components or routes.
```

Name and describe at least two layers of an Ember application:

```md
- Ember Router (`Ember.Router`) --> Reads the URL and tells Ember what you want to view
- Ember Route (`Ember.Route`) --> When we set up a route, we map all our components to a function... this is where we sort of represent the `controller`
- Adapter (`DS.RESTAdapter`) --> This manages the relationship between the resource and the local storage
```

How does a component differ from an Ember template?

```md
A component is invoked from _within_ a template... Its scope gets defined where the component is invoked, so it can't access the global scop.
```

What is an opinionated framework? Is Ember opinionated? How or how not?

```md
An opinionated framework is one in which developers can make assumptions. Following convention works under the assumption that everyone else is following convention, so yea, I would argue that Ember is opinionated since it does exactly that. This helps keep Ember DRY, too.
```

In Ember what is a route's job (please list three)?

```md
- Tells the router what route objects to look for
- Points the router to the path linked to the route object
    - The default path is the name of the route object, but a path argument can be made for each route if need be
- Defines nested routes, if any
    - For example, if I have a route `team` that has a sub-route `leadership`, the `leadership` route would be defined within a function inside the `team` route
```

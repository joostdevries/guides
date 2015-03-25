These guides will take you through the various aspects of Ember and your application.

## Use the built-in code-generators

Ember is a framework that favors Convention over Configuration. Because you might not now all conventions straight away, we've made sticking to them very easy by providing code generation for practically every type of module your app could need. To get an overview of all, run:

```bash
ember help generate
```

## ES6 modules and imports

When you're not using the built-in generators, make sure you're always importing any module you're using. This includes importing `Ember` from the 'ember' module and `DS` from the 'ember-data' packages.

```bash
import Ember from 'ember';
import DS from 'ember-data'; // Only when using Ember Data
```

## Creating an app

Creating an app is as easy as running `ember new <app-name>`:

```bash
ember new my-app
```
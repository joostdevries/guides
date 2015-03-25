The Ember guides will take you through the various aspects of your applciation and the framework. To make your work easy, we've got two tips for you:

## 1. Use the built-in code-generators

Ember is a framework that favors Convention over Configuration. Because you might not now all conventions straight away, we've made sticking to them very easy by providing code generation for practically every type of module your app could need. To get an overview of all, run:

```bash
ember help generate
```

## 2. Use ES6 modules and imports properly

Ember uses [ES6 modules](http://eviltrout.com/2014/05/03/getting-started-with-es6.html) to organize your application's code. When you're not using the built-in generators, make sure you're always importing any module you're using. This includes importing `Ember` from the 'ember' module and `DS` from the 'ember-data' packages. Failing to do so will result in errors in your console (`Ember is not defined`).

```bash
import Ember from 'ember';
import DS from 'ember-data'; // Only when using Ember Data
```

## Creating an app

Now for the most important step: creating your app. This is as easy as running `ember new <app-name>`.

```bash
ember new my-app
```
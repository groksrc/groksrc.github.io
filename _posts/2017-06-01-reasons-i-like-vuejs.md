---
title: Reasons I Like Vue.js
---

[Vue.js](https://vuejs.org) has recently become my go-to front end framework. I like it because it's easy to get started with and you can use it for anything from simple tasks to complex enterprise applications. Here are the reasons why I like Vue.js:

## The API is Stable
I really like how Evan and the core contributors have defined a nice API and they don't feel or see the need to overhaul it often. Sure it is changing and improving over time, but it's not a constant revolutionary change.

> <i>me: gives side-eye to webpack</i> 👀

## The API is easy to understand
You have in the API exactly what you would expect: A well defined, easy to follow event lifecycle for components that define a series of steps to go through to render some html.

The real beauty of the vue.js approach is the ability to define html and javascript in the same file, but separate the markup from the javascript. It makes the code familiar, easier to read, and to reason about.

Contrast with React the blurring of html, xml and javascript into jsx. The entire learning curve is avoided in vue.js, and we follow the same paradigms that we have traditionally followed. Your view code and model/controller code remain separate and distinct. Simple.

## The Style Guide
The [Vue.js Style Guide](https://vuejs.org/v2/style-guide/) is a fantastic way to define cohesion in the community around best practices and what a cannonical code base should look like.

You may or may not like every rule and suggestion that they define, but they at least contribute to what you should be thinking about and you should have just cause to deviate from them.

By following the conventions, the broader community benefits as we collaborate with a shared understanding of how things should be put together. It increases productivity and reduces the number of things to actually think about as you implement your project requirements.

## vue-router and vuex
It's unfortunate (imho) that React doesn't take a more pronounced approach on what is recommended when dealing with routing or storage. Though clearly react-redux and react-router are some common go-tos, there are many, many options. And while React works well together with these libraries we're told that the relationship is not explicit. In fact, the first line of the [Redux docs](https://redux.js.org/basics/usage-with-react) state that "Redux has no relation to React".

<div class="message">
  From the very beginning, we need to stress that Redux has no relation to React. You can write Redux apps with React, Angular, Ember, jQuery, or vanilla JavaScript.
</div>

With vue-router and vuex we are given the recommended path, which in cases of frameworks like this, happens to be exceedingly helpful. It reduces the amount of discovery necessary and leads you to more consistent implementations across projects. In a large environment I find this point to be expecially compelling.

## Summary
I'm sorry for any react fans I may have rubbed the wrong way. This wasn't to bash React as much as it was to talk up the benefits of vue.js and React is obviously a primary basis for comparison. React is clearly a popular choice, and valuable technology. But I hope you have the chance to spend some time with vue.js. It's a great framework for small and large projects. It has my full throated endorsement.

g

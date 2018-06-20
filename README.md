# Vuex [![Build Status](https://circleci.com/gh/vuejs/vuex/tree/dev.png?style=shield)](https://circleci.com/gh/vuejs/vuex)

> Centralized State Management for Vue.js with Support for [fluture Futures](https://github.com/fluture-js/Fluture).

<p align="center">
  <img width="700px" src="https://raw.githubusercontent.com/vuejs/vuex/dev/docs/.vuepress/public/vuex.png">
</p>

- [What is Vuex?](https://vuex.vuejs.org/)
- [Full Documentation](http://vuex.vuejs.org/)

## Examples

- [Counter](https://github.com/vuejs/vuex/tree/dev/examples/counter)
- [Counter with Hot Reload](https://github.com/vuejs/vuex/tree/dev/examples/counter-hot)
- [TodoMVC](https://github.com/vuejs/vuex/tree/dev/examples/todomvc)
- [Flux Chat](https://github.com/vuejs/vuex/tree/dev/examples/chat)
- [Shopping Cart](https://github.com/vuejs/vuex/tree/dev/examples/shopping-cart)

Running the examples:

``` bash
$ npm install
$ npm run dev # serve examples at localhost:8080
```


## Why this fork

I really like the fluture library.

So much that I avoid using Promises if possible and use Futures instead.

Go there and read some of the linked articles, if you don't know what futures are. They are worth it.

## Notable points about this fork

The TypeScript are not implemented correctly, since I have no experience with TypeScript.

Also I've removed the e2e tests for the examples, since the original tests were failing for me and I didn't want to fix them *and* update the tests. If someone likes fluture enough to contribute, please do. 

## License

[MIT](http://opensource.org/licenses/MIT)

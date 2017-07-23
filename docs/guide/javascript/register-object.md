
# Register your first object

To start working with dop the first thing we have to do is register a [POJO object](https://en.wikipedia.org/wiki/Plain_old_Java_object) with the initial state of our APP.

```js
const state = dop.register({
    todos: [],
    completedCount: 0
})
console.log(state.todos.length) // 0
```

Register will return an [ES6 Proxy object](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Proxy). Basically, we have created an observable object where can be observed when mutates.





*For a more detailed documentation have a look [register](/api/javascript/register)*





> #### Next step
> [Create an observer](/guide/javascript/create-observer)

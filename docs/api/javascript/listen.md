# listen( [options] )

> Creates a new [Listener](/api/javascript/Listener) instance that listen for new [connections/nodes](/api/javascript/node).

## Arguments

#### [options] `Object`
- *[transport](/transports/javascript/websockets)* `Function` By default is WebSockets ([ws](https://github.com/websockets/ws)) on node.js

## Returns

A new [Listener](/api/javascript/Listener) instance.


## Examples
```js
const dop = require('dop')
const listener = dop.listen()
```


> See also
- [connect](/api/javascript/connect)
- [WebSockets transport](/transports/javascript/websockets)
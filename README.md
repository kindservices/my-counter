# About

this is a svelte component which gets consumed by a container.

It exposes a 'bundle.js' and 'bundle.css' which can be imported at runtime from a host container which provide the components:

## my-counter
 * [my-card](./src/lib/My Counter.svelte)
 * [my-counter](./src/lib/Counter.svelte)

See the [Makefile](./Makefile) for build targets

## Running / Testing 

To test locally, you can use `make run`, then open either [a static test page](./test/local-test.html) or a [dynamic load](./test/dynamic-test.html) in your browser


# References
See [here](https://www.colorglare.com/svelte-components-as-web-components-b400d1253504)
and [here](https://medium.com/javascript-by-doing/how-to-create-a-web-component-in-svelte-5963356ec978)
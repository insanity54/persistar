# datastar-persist

https://data-star.dev offers a [persistence plugin](https://data-star.dev/reference/attributes#data-persist), but it's closed source and cost $349. This one is free.


## Usage

### Make sure you have datastar imported

```html
https://cdn.jsdelivr.net/gh/starfederation/datastar@1.0.0-RC.7/bundles/datastar.js
```

### Import the datastar-persist plugin

```html
<script type="module" src="https://cdn.jsdelivr.net/gh/insanity54/datastar-persist/dist/index.js"></script>
```

### Use the plugin

```html
<div data-signals:count="0" data-persist="count">
  <p>Counter: <strong data-text="$count">0</strong></p>
  <button data-on:click="$count++">Increment</button>
  <button data-on:click="$count--">Decrement</button>
  <button data-on:click="$count=0">Reset</button>
</div>
```

## Advanced usage

### Supports nested variables

```html
```

### Supports debouncing

Debouncing prevents the storage from being written to until the input hasn't changed for n milliseconds.

```html

```

## Upstream References

* https://github.com/ndendic/data-persist
* https://github.com/banditburai/starHTML/blob/main/typescript/handlers/persist.ts
* https://github.com/starfederation/datastar/blob/a02c0f15a98465b1da24834c8ab9c9842c82fd18/code/ts/library/src/plugins/official/attributes/storage/persist.ts
* https://starhtml.com/static/js/handlers/persist.js


# Hire the maintainer

Hello! I’m Chris Grimmett, and I'm currently seeking short-term projects. If you're interested in collaborating, feel free to reach me via email at [chris@grimtech.net](mailto:chris@grimtech.net).
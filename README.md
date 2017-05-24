# vue-grid
> A flexible grid component for Vue.js

vue-grid is designed to be an advanced [Vue.js](http://vuejs.org) grid component allowing for fast loading and rendering of tabular data.

## Documentation
[https://github.com/dzwillia/vue-grid/](https://github.com/dzwillia/vue-grid/)

## Demo

[https://dzwillia.github.io/vue-grid](https://dzwillia.github.io/vue-grid)

## Requirements
* [Vue.js](http://vuejs.org/) (^v2.1.4)

## Browser support
IE 10+ (due to [Flexbox support](https://caniuse.com/#feat=flexbox)).

## Installation

### NPM

```bash
npm install vue2-grid --save
```

### Usage

### ES6

```js
<grid
  data-url="https://enter-your-data/url/endpoint/here"
></grid>
```

Please note that for now he JSON payload must be formatted as follows:

```json
{
  columns: [
    { name: "col1" },
    { name: "col2" },
    { name: "col3" },
    ...
  ],
  rows: [
    0: { col1: "Column 1 Value 1", col2: "Column 2 Value 1", col3: "Column 3 Value 1" },
    0: { col1: "Column 1 Value 2", col2: "Column 2 Value 2", col3: "Column 3 Value 2" },
    0: { col1: "Column 1 Value 3", col2: "Column 2 Value 3", col3: "Column 3 Value 3" },
    ...
  ],
  total_count: 1000
}
```

The columns node only needs to be provided on the first call.

## License
vue-grid is open source and released under the [MIT License](LICENSE).

Copyright (c) 2017 [David Z Williams](https://twitter.com/padredaveo).

> *PS: I would love to know if you're using vue-grid. Tweet to me at [@padredaveo](https://twitter.com/padredaveo)*.

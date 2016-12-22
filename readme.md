# residual-scroll-top [![Build Status](https://travis-ci.org/akameco/residual-scroll-top.svg?branch=master)](https://travis-ci.org/akameco/residual-scroll-top)

> Residual Scroll


## Install

```
$ npm install --save residual-scroll-top
```


## Usage

```js
const residualScrollTop = require('residual-scroll-top');

residualScrollTop(node, () => {
	console.log('Scroll Top');
});
```

## API

### residualScrollTop(node, ?callback)

#### node

Type: `HTMLElement`

#### callback

Type: `Function`

Called when arriving at top.

## License

MIT © [akameco](http://akameco.github.io)

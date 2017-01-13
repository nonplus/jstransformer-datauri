# jstransformer-datauri

[Data URI](https://en.wikipedia.org/wiki/Data_URI_scheme) support for [JSTransformers](http://github.com/jstransformers).

## Installation

    npm install jstransformer-datauri

## API

```js
var datauri = require('jstransformer')(require('jstransformer-datauri'))

datauri.renderFile('image.png').body
//=> 'data:image/png;base64,iVBORw...'
```

## License

MIT

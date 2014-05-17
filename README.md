## broccoli-base64-css

[Broccoli](https://github.com/broccolijs/broccoli) plugin to replace refrences to images in CSS with base64 strings.

### Install
```
npm install --save broccoli-base64-css
```

### Example
```js
var base64CSS = require('broccoli-base64-css');

// Example with default options
var tree = base64CSS(tree, {
  imagePath: 'public'
, maxFilesize: 4096 // larger files will be left untouched
, extensions: ['css']
});
```


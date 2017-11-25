# vue-less-format
This is simply [vue-css-format](https://github.com/linrui1994/vue-css-format) and [postcss-format-less-mixins](https://github.com/frontendauteur/postcss-format-less-mixins) put together.

# usage
- install
```shell
npm install vue-less-format --save-dev
```

- write the following js file
```javascript
var format = require('vue-less-format');
var path = require('path')

format(path.resolve()) // the directory want to format
```

- run the js code
```shell
node index.js
```

### License
The MIT License

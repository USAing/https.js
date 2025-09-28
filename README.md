
# https.js

[![codecov](https://badge.eu.org/static/codecov/555/95/4c1?icon=codecov)](https://codecov.io/gh/USAing/https.js)
[![TAG](https://badge.eu.org/github/tag/USAing/https.js?icon=github)](../../releases)
[![NPM](https://badge.eu.org/npm/version/https.js?icon=npm)](https://www.npmjs.com/package/https.js)

[![Package](https://badge.eu.org/npm/package/https.js)](https://www.npmjs.com/package/https.js)

This is a pure JavaScript small program, does not need third-party software support

## Features

- Pure JavaScript writing
- A simple class file

## Installation

Use [Node.js](https://nodejs.org/) to install the library. Of course, You can go to [package](https://www.npmjs.com/package/https.js) to view.

```console
npm i https.js
```

## Code Example

```javascript
var url = "https://example.com";
var res_function = function(res, status) {
  if( status == 200){ //ok
  	var responseText = JSON.parse(res);
  	// responseText
  }
}

var ARGUMENTS = {URL:url, RES_FUNCTION:res_function, HEADER:{'Content-type':'application/json;charset=UTF-8'}};

https(ARGUMENTS);
```
If you need to learn more, go to [more examples](https://https.js.org/pages/Example.html).

## License

[![MPL-2.0](https://badge.eu.org/static/license/555/MPL-2.0/FE7D37?icon=github)](LICENSE)

# https.js

[![codecov](https://badging.vercel.app/codecov/coverage/gh/yakeing/https.js?icon=codecov&branch=main)](https://codecov.io/gh/yakeing/https.js)
[![TAG](https://badging.vercel.app/github/tag/yakeing/https.js?icon=github)](../../releases)
[![NPM](https://badging.vercel.app/npm/version/https.js?icon=npm)](https://www.npmjs.com/package/https.js)

[![Package](https://badging.vercel.app/npm/package/https.js)](https://www.npmjs.com/package/https.js)

[![codecov-totals](https://badging.vercel.app/codecov/totals/gh/yakeing/https.js)](https://codecov.io/gh/yakeing/https.js)

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

## Author

weibo: [yakeing](https://weibo.com/yakeing)

twitter: [yakeing](https://twitter.com/yakeing)

## License

[![MPL-2.0](https://badging.vercel.app/static/license/555/MPL-2.0/FE7D37?icon=github)](LICENSE)

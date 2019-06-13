# is-ua-webview

  A super simple webview user-agent detector

  [![Build Status](https://travis-ci.org/atomantic/is-ua-webview.png)](https://travis-ci.org/atomantic/is-ua-webview)  [![](https://img.shields.io/npm/dm/is-ua-webview.svg?style=flat)](https://www.npmjs.org/package/is-ua-webview)
  [![](https://img.shields.io/npm/v/is-ua-webview.svg?style=flat)](https://www.npmjs.org/package/is-ua-webview)
  [![](https://img.shields.io/david/atomantic/is-ua-webview.svg?style=flat)](https://www.npmjs.org/package/is-ua-webview)


## Installation

    $ npm install is-ua-webview

## Usage

```js
var isWebview = require('is-ua-webview')

// just for testing:
var assert = require('assert')

// identifies googlebot as bot (returns true)
assert(isWebview('Mozilla/5.0 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)'))

// Android Pixel is not a bot (returns false)
assert(!isWebview('Android 7.1; Pixel Build/NDE63P)'))
```

## Tests

Run tests
```bash
npm test
```


## Author

Adam Eivy is a software architect by day and a drawing dad by night: [follow him on the interwebs](http://adameivy.com)

[![follow](https://img.shields.io/twitter/follow/antic.svg?style=social&label=Follow)](https://twitter.com/antic)

Got a giggle worthy of a tip? 
⚡ Lightning Bitcoin Tips Accepted https://tippin.me/@antic

# gfm-code-block-regex [![NPM version](https://badge.fury.io/js/gfm-code-block-regex.png)](http://badge.fury.io/js/gfm-code-block-regex)

> RegExp for gfm (GitHub Flavored Markdown) code blocks.

## Install
#### Install with [npm](npmjs.org):

```bash
npm i gfm-code-block-regex --save-dev
```

## Usage

```js
var re = require('gfm-code-block-regex')();
var code = ('\n```js\nfoo\n```\n').match(re);
console.log(RegExp.$1);
//=> '\nfoo\n'
console.log(RegExp.$2);
//=> 'js'
```

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014 Jon Schlinkert, contributors.  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on August 13, 2014._
# package-info 

> Get the information of a npm package

Fetches the information directly from the registry 

https://www.npmjs.org/package/package-info

To create this repository I have forked this project and make some edit:

https://github.com/sindresorhus/npm-name

Thanks to the author https://github.com/sindresorhus

The information that you can retrieve are:
- <b>package name</b>
- <b>package version</b>
- <b>package description</b>
- <b>package license</b>
- <b>author name</b>

## Install

```sh
$ npm install --save package-info
```


## Usage

```js
var info = require('package-info');

info('pageres', function (err, version) {
	console.log(version);
});
```

## CLI

```sh
$ npm install --global package-info
```

```sh
$ package-info --help

Usage
  $ package-info <package-name>

Example
  $ package-info package-info
```

It prints:
```
name: package-info 
version: 0.1.3 
description: Get the information of a npm package 
license: MIT 
author: Alessandro Minoccheri
```

## License

The MIT License (MIT)

Copyright (c) 2014 Alessandro Minoccheri

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


# Client Library for the Dropbox API

This is a JavaScript client for the Dropbox API, suitable for use in both
modern browsers and in server-side code running under
[node.js](http://nodejs.org/).


## Installation

The library can be included in client-side applications using the following
HTML snippet.

```html
<script type="text/javascript" src="http://TODO">
</script>
```

The library is also available as an [npm](http://npmjs.org/) package, and can
be installed using the following command.

```bash
npm install dropbox-4real
```


## Usage

TBD


## Development

The library is written using [CoffeeScript](http://coffeescript.org/), packaged
using [uglify.js](https://github.com/mishoo/UglifyJS/), and tested using
[mocha](http://visionmedia.github.com/mocha/).


### Running the Tests

First install [node.js](http://nodejs.org/#download) to get `npm` (the node
package manager), then use it to install the libraries required by the test
suite. Last, use `cake` to run the test suite.

```bash
git clone https://github.com/pwnall/dropbox-sdk.git
cd dropbox-sdk
npm install -g coffee-script mocha uglify-js
npm install
cake test
```


## Copyright and License

The library is (c) Copyright Dropbox, Inc. 2012, and distributed under the MIT
License.


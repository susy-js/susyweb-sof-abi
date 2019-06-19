# susyweb-sof-abi

This is a sub package of [susyweb.js][repo]

This is the abi package to be used in the `susyweb-sof` package.
Please read the [documentation][docs] for more.

## Installation

### Node.js

```bash
npm install susyweb-sof-abi
```

### In the Browser

Build running the following in the [susyweb.js][repo] repository:

```bash
npm run-script build-all
```

Then include `dist/susyweb-sof-abi.js` in your html file.
This will expose the `SusyWebSofAbi` object on the window object.


## Usage

```js
// in node.js
var SusyWebSofAbi = require('susyweb-sof-abi');

SusyWebSofAbi.encodeFunctionSignature('myMethod(uint256,string)');
> '0x24ee0097'
```


[docs]: http://susywebjs.readthedocs.io/en/1.0/
[repo]: https://octonion.institute/susy-js/susyweb.js



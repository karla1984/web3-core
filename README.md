# web3-core

This is a sub-package of [web3.js][repo].

The core package contains core functions for [web3.js][repo] packages.

Please read the [documentation][docs] for more.

## Installation

### Node.js

```bash
npm install @karla1984/web3-core
```

## Usage

```js
const core = require('@karla1984/web3-core');

const CoolLib = function CoolLib() {
    // sets _requestmanager and adds basic functions
    core.packageInit(this, arguments);
};

CoolLib.providers;
CoolLib.givenProvider;
CoolLib.setProvider();
CoolLib.BatchRequest();
CoolLib.extend();
...
```

## Types

All the TypeScript typings are placed in the `types` folder.

[docs]: http://web3js.readthedocs.io/en/1.0/
[repo]: https://github.com/ethereum/web3.js
[npm-image]: https://img.shields.io/npm/v/web3-core.svg
[npm-url]: https://npmjs.org/package/web3-core
[deps-image]: https://david-dm.org/ethereum/web3.js/1.x/status.svg?path=packages/web3-core
[deps-url]: https://david-dm.org/ethereum/web3.js/1.x?path=packages/web3-core
[deps-dev-image]: https://david-dm.org/ethereum/web3.js/1.x/dev-status.svg?path=packages/web3-core
[deps-dev-url]: https://david-dm.org/ethereum/web3.js/1.x?type=dev&path=packages/web3-core

# npmtest-coinbase-exchange

#### test coverage for  [coinbase-exchange (v0.2.2)](https://github.com/coinbase/coinbase-exchange-node)  [![npm package](https://img.shields.io/npm/v/npmtest-coinbase-exchange.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-coinbase-exchange) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-coinbase-exchange.svg)](https://travis-ci.org/npmtest/node-npmtest-coinbase-exchange)

#### Client for the Coinbase Exchange API

[![NPM](https://nodei.co/npm/coinbase-exchange.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/coinbase-exchange)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-coinbase-exchange/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-coinbase-exchange/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-coinbase-exchange/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-coinbase-exchange/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-coinbase-exchange/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-coinbase-exchange/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-coinbase-exchange/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-coinbase-exchange/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-coinbase-exchange/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-coinbase-exchange/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-coinbase-exchange/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-coinbase-exchange/build/test-report.html](https://npmtest.github.io/node-npmtest-coinbase-exchange/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-coinbase-exchange/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-coinbase-exchange/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-coinbase-exchange/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-coinbase-exchange/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-coinbase-exchange/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-coinbase-exchange/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-coinbase-exchange/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-coinbase-exchange/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Coinbase"
    },
    "bugs": {
        "url": "https://github.com/coinbase/coinbase-exchange-node/issues"
    },
    "contributors": [
        {
            "name": "Peter Downs",
            "url": "http://peterdowns.com"
        },
        {
            "name": "Maksim Stepanenko",
            "url": "http://maksim.ms"
        }
    ],
    "dependencies": {
        "async": "1.5.0",
        "bintrees": "1.0.0",
        "lodash.assign": "3.0.0",
        "lodash.foreach": "3.0.0",
        "lodash.partial": "3.0.0",
        "nock": "3.6.0",
        "num": "0.2.1",
        "request": "2.74.0",
        "ws": "1.1.1"
    },
    "deprecated": "WARNING: This module has been renamed to gdax. Please install it instead.",
    "description": "Client for the Coinbase Exchange API",
    "devDependencies": {
        "mocha": "1.20.1",
        "nsp": "2.6.1"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "bee69f85ec513952f2cd433d0c72c832cdf83331",
        "tarball": "https://registry.npmjs.org/coinbase-exchange/-/coinbase-exchange-0.2.2.tgz"
    },
    "gitHead": "50185a16641d991dfe7914955be98e1d0c83ac00",
    "homepage": "https://github.com/coinbase/coinbase-exchange-node",
    "keywords": [
        "API",
        "bitcoin",
        "coinbase",
        "exchange",
        "real-time",
        "trading",
        "websockets"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "amacneil"
        },
        {
            "name": "defunctzombie"
        },
        {
            "name": "maksim"
        },
        {
            "name": "peterldowns"
        }
    ],
    "name": "coinbase-exchange",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/coinbase/coinbase-exchange-node.git"
    },
    "scripts": {
        "scan_packages": "nsp check --output summary",
        "test": "mocha --ui qunit --bail --reporter list tests/*.js"
    },
    "version": "0.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

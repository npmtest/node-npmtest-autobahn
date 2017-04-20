# npmtest-autobahn

#### basic test coverage for  [autobahn (v0.12.0)](https://github.com/crossbario/autobahn-js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-autobahn.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-autobahn) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-autobahn.svg)](https://travis-ci.org/npmtest/node-npmtest-autobahn)

#### An implementation of The Web Application Messaging Protocol (WAMP).

[![NPM](https://nodei.co/npm/autobahn.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/autobahn)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-autobahn/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-autobahn/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-autobahn/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-autobahn/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-autobahn/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-autobahn/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-autobahn/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-autobahn/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-autobahn/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-autobahn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-autobahn/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-autobahn/build/test-report.html](https://npmtest.github.io/node-npmtest-autobahn/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-autobahn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-autobahn/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-autobahn/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-autobahn/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-autobahn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-autobahn/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-autobahn/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-autobahn/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Crossbar.io Technologies GmbH"
    },
    "browser": {
        "ws": false,
        "lib/transport/rawsocket.js": false
    },
    "bugs": {
        "url": "https://github.com/crossbario/autobahn-js/issues"
    },
    "dependencies": {
        "bufferutil": ">= 1.2.1",
        "cbor": ">= 3.0.0",
        "crypto-js": ">= 3.1.8",
        "google-closure-compiler": "^20170218.0.0",
        "int64-buffer": ">= 0.1.9",
        "msgpack-lite": ">= 0.1.26",
        "tweetnacl": ">= 0.14.3",
        "utf-8-validate": ">= 1.2.1",
        "when": ">= 3.7.7",
        "ws": ">= 1.1.4"
    },
    "description": "An implementation of The Web Application Messaging Protocol (WAMP).",
    "devDependencies": {
        "browserify": ">= 13.1.1",
        "deep-equal": ">= 1.0.1",
        "nodeunit": ">= 0.10.2"
    },
    "directories": {},
    "dist": {
        "shasum": "00789b599a0da4c2d634cb1c1557e339d53cecf8",
        "tarball": "https://registry.npmjs.org/autobahn/-/autobahn-0.12.0.tgz"
    },
    "engines": {
        "node": ">= 4.2.6"
    },
    "gitHead": "79b093bf47f6ff3e2fd50f42fce20578150baaf9",
    "homepage": "https://github.com/crossbario/autobahn-js#readme",
    "keywords": [
        "WAMP",
        "WebSocket",
        "RPC",
        "PubSub"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "goeddea"
        },
        {
            "name": "oberstet"
        }
    ],
    "name": "autobahn",
    "optionalDependencies": {
        "bufferutil": ">= 1.2.1",
        "utf-8-validate": ">= 1.2.1"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/crossbario/autobahn-js.git"
    },
    "scripts": {
        "test": "nodeunit test/test.js"
    },
    "version": "0.12.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

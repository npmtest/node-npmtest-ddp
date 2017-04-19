# npmtest-ddp

#### basic test coverage for  [ddp (v0.12.1)](https://github.com/oortcloud/node-ddp-client#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ddp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ddp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ddp.svg)](https://travis-ci.org/npmtest/node-npmtest-ddp)

#### Node.js module to connect to servers using DDP protocol.

[![NPM](https://nodei.co/npm/ddp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ddp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ddp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ddp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ddp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ddp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ddp/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ddp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ddp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ddp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ddp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ddp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ddp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ddp/build/test-report.html](https://npmtest.github.io/node-npmtest-ddp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ddp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ddp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ddp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ddp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ddp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ddp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ddp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ddp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tom Coleman",
        "url": "http://tom.thesnail.org"
    },
    "bugs": {
        "url": "https://github.com/oortcloud/node-ddp-client/issues"
    },
    "contributors": [
        {
            "name": "Thomas Sarlandie",
            "url": "http://www.sarfata.org"
        },
        {
            "name": "Mason Gravitt"
        },
        {
            "name": "Mike Bannister",
            "url": "http://po.ssibiliti.es"
        },
        {
            "name": "Chris Mather",
            "url": "http://eventedmind.com"
        },
        {
            "name": "Tarang Patel"
        },
        {
            "name": "Vaughn Iverson"
        },
        {
            "name": "Rony Kubat"
        }
    ],
    "dependencies": {
        "ddp-ejson": "0.8.1-3",
        "ddp-underscore-patched": "0.8.1-2",
        "faye-websocket": "0.11.0",
        "request": "2.74.x"
    },
    "description": "Node.js module to connect to servers using DDP protocol.",
    "devDependencies": {
        "mocha": "~3.0.2",
        "rewire": "~2.5.2",
        "sinon": "~1.17.5"
    },
    "directories": {},
    "dist": {
        "shasum": "1443514c3c1334a5fdb3dfae7a180a4f698105b7",
        "tarball": "https://registry.npmjs.org/ddp/-/ddp-0.12.1.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "2a1e95b8db35440211f2e3752a46005387803bd8",
    "homepage": "https://github.com/oortcloud/node-ddp-client#readme",
    "keywords": [
        "ddp",
        "meteor",
        "protocol"
    ],
    "license": "MIT",
    "main": "lib/ddp-client",
    "maintainers": [
        {
            "name": "tmeasday"
        },
        {
            "name": "possibilities"
        },
        {
            "name": "sarfata"
        },
        {
            "name": "emgee"
        },
        {
            "name": "tarang"
        },
        {
            "name": "vsivsi"
        }
    ],
    "name": "ddp",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/oortcloud/node-ddp-client.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha test"
    },
    "version": "0.12.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

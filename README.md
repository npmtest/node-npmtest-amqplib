# test coverage for  [amqplib (v0.5.1)](http://squaremo.github.io/amqp.node/)  [![npm package](https://img.shields.io/npm/v/npmtest-amqplib.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-amqplib) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-amqplib.svg)](https://travis-ci.org/npmtest/node-npmtest-amqplib)
#### An AMQP 0-9-1 (e.g., RabbitMQ) library and client.

[![NPM](https://nodei.co/npm/amqplib.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/amqplib)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-amqplib/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-amqplib/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-amqplib/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-amqplib/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-amqplib/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-amqplib/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-amqplib/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-amqplib/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-amqplib/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-amqplib/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-amqplib/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-amqplib/build/test-report.html](https://npmtest.github.io/node-npmtest-amqplib/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-amqplib/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-amqplib/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-amqplib/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-amqplib/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-amqplib/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-amqplib/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-amqplib/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-amqplib/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Bridgen"
    },
    "bugs": {
        "url": "https://github.com/squaremo/amqp.node/issues"
    },
    "dependencies": {
        "bitsyntax": "~0.0.4",
        "bluebird": "^3.4.6",
        "buffer-more-ints": "0.0.2",
        "readable-stream": "1.x >=1.1.9"
    },
    "description": "An AMQP 0-9-1 (e.g., RabbitMQ) library and client.",
    "devDependencies": {
        "claire": "0.4.1",
        "istanbul": "0.1.x",
        "mocha": "~1",
        "uglify-js": "2.4.x"
    },
    "directories": {},
    "dist": {
        "shasum": "7cccfebabe56c2e984ea7a2243f7cefe6fbfc6cf",
        "tarball": "https://registry.npmjs.org/amqplib/-/amqplib-0.5.1.tgz"
    },
    "engines": {
        "node": ">=0.8 <6 || ^6"
    },
    "gitHead": "b21133d708fbb9677267428dd74ddb7fe7f1f80e",
    "homepage": "http://squaremo.github.io/amqp.node/",
    "keywords": [
        "AMQP",
        "AMQP 0-9-1",
        "RabbitMQ"
    ],
    "license": "MIT",
    "main": "./channel_api.js",
    "maintainers": [
        {
            "name": "squaremo"
        }
    ],
    "name": "amqplib",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/squaremo/amqp.node.git"
    },
    "scripts": {
        "prepublish": "make",
        "test": "make test"
    },
    "version": "0.5.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

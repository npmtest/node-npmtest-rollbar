# npmtest-rollbar

#### basic test coverage for  [rollbar (v0.6.5)](https://rollbar.com/docs/notifier/node_rollbar/)  [![npm package](https://img.shields.io/npm/v/npmtest-rollbar.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rollbar) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rollbar.svg)](https://travis-ci.org/npmtest/node-npmtest-rollbar)

#### A standalone (Node.js) client for Rollbar

[![NPM](https://nodei.co/npm/rollbar.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rollbar)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rollbar/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rollbar/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rollbar/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rollbar/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rollbar/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rollbar/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rollbar/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rollbar/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rollbar/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rollbar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rollbar/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rollbar/build/test-report.html](https://npmtest.github.io/node-npmtest-rollbar/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rollbar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rollbar/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rollbar/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rollbar/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rollbar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rollbar/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rollbar/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rollbar/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rollbar, Inc."
    },
    "bugs": {
        "url": "https://github.com/rollbar/node_rollbar/issues"
    },
    "dependencies": {
        "async": "~1.2.1",
        "debug": "2.2.0",
        "decache": "^3.0.5",
        "json-stringify-safe": "~5.0.0",
        "lru-cache": "~2.2.1",
        "request-ip": "~1.2.3",
        "uuid": "~3.0.0"
    },
    "description": "A standalone (Node.js) client for Rollbar",
    "devDependencies": {
        "express": "*",
        "jade": "~0.27.7",
        "sinon": "1.16.1",
        "vows": "~0.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e20352201fdab79b96e3c6a02d7f4a12c3dc2dfe",
        "tarball": "https://registry.npmjs.org/rollbar/-/rollbar-0.6.5.tgz"
    },
    "engines": {
        "node": ">= 0.6.0"
    },
    "gitHead": "cd5953564b59426bae9ad94848bcc2c7bca017a9",
    "homepage": "https://rollbar.com/docs/notifier/node_rollbar/",
    "keywords": [
        "rollbar",
        "exception",
        "uncaughtException",
        "error",
        "ratchetio",
        "ratchet"
    ],
    "license": "MIT",
    "main": "rollbar",
    "maintainers": [
        {
            "name": "brianr"
        },
        {
            "name": "coryvirok"
        },
        {
            "name": "dampier"
        },
        {
            "name": "jfarrimo"
        },
        {
            "name": "jondeandres"
        },
        {
            "name": "rokob"
        }
    ],
    "name": "rollbar",
    "optionalDependencies": {
        "decache": "^3.0.5"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/rollbar/node_rollbar.git"
    },
    "scripts": {
        "test": "vows --spec test/*.js",
        "test-and-coverage": "istanbul cover -- vows --spec test/*.js"
    },
    "version": "0.6.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

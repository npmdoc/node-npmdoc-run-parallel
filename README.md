# npmdoc-run-parallel

#### api documentation for  [run-parallel (v1.1.6)](https://github.com/feross/run-parallel)  [![npm package](https://img.shields.io/npm/v/npmdoc-run-parallel.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-run-parallel) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-run-parallel.svg)](https://travis-ci.org/npmdoc/node-npmdoc-run-parallel)

#### Run an array of functions in parallel

[![NPM](https://nodei.co/npm/run-parallel.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/run-parallel)

- [https://npmdoc.github.io/node-npmdoc-run-parallel/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-run-parallel/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-run-parallel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-run-parallel/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-run-parallel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-run-parallel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Feross Aboukhadijeh",
        "url": "http://feross.org/"
    },
    "bugs": {
        "url": "https://github.com/feross/run-parallel/issues"
    },
    "dependencies": {},
    "description": "Run an array of functions in parallel",
    "devDependencies": {
        "standard": "^6.0.5",
        "tape": "^4.0.0",
        "zuul": "^3.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "29003c9a2163e01e2d2dfc90575f2c6c1d61a039",
        "tarball": "https://registry.npmjs.org/run-parallel/-/run-parallel-1.1.6.tgz"
    },
    "gitHead": "f9ee5e836569ec13712889a208a0a730069e22af",
    "homepage": "https://github.com/feross/run-parallel",
    "keywords": [
        "parallel",
        "async",
        "function",
        "callback",
        "asynchronous",
        "run",
        "array",
        "run parallel"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "feross"
        }
    ],
    "name": "run-parallel",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/feross/run-parallel.git"
    },
    "scripts": {
        "test": "standard && npm run test-node && npm run test-browser",
        "test-browser": "zuul -- test/*.js",
        "test-browser-local": "zuul --local -- test/*.js",
        "test-node": "tape test/*.js"
    },
    "version": "1.1.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

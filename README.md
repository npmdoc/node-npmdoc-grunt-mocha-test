# npmdoc-grunt-mocha-test

#### api documentation for  [grunt-mocha-test (v0.13.2)](https://github.com/pghalliday/grunt-mocha-test)  [![npm package](https://img.shields.io/npm/v/npmdoc-grunt-mocha-test.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-grunt-mocha-test) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-grunt-mocha-test.svg)](https://travis-ci.org/npmdoc/node-npmdoc-grunt-mocha-test)

#### A grunt task for running server side mocha tests

[![NPM](https://nodei.co/npm/grunt-mocha-test.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-mocha-test)

- [https://npmdoc.github.io/node-npmdoc-grunt-mocha-test/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-mocha-test/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-mocha-test/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-mocha-test/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-grunt-mocha-test/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-grunt-mocha-test/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-mocha-test",
    "description": "A grunt task for running server side mocha tests",
    "version": "0.13.2",
    "homepage": "https://github.com/pghalliday/grunt-mocha-test",
    "author": {
        "name": "Peter Halliday",
        "url": "http://pghalliday.github.io/"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/pghalliday/grunt-mocha-test.git"
    },
    "bugs": {
        "url": "https://github.com/pghalliday/grunt-mocha-test/issues"
    },
    "license": "MIT",
    "engines": {
        "node": ">= 0.10.4"
    },
    "scripts": {
        "test": "grunt",
        "ci": "grunt ci"
    },
    "config": {
        "travis-cov": {
            "threshold": 100
        }
    },
    "dependencies": {
        "hooker": "^0.2.3",
        "mkdirp": "^0.5.0"
    },
    "peerDependencies": {
        "mocha": ">=1.20.0"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "coffee-script": "^1.10.0",
        "grunt": "^1.0.1",
        "grunt-cli": "^1.2.0",
        "grunt-continue": "^0.1.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-coveralls": "^1.0.1",
        "grunt-env": "^0.4.4",
        "grunt-istanbul": "^0.7.1",
        "grunt-istanbul-coverage": "^0.1.4",
        "mocha": "^3.0.2",
        "rimraf": "^2.5.0"
    },
    "keywords": [
        "gruntplugin",
        "mocha",
        "test"
    ],
    "files": [
        "tasks",
        "LICENSE-MIT"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

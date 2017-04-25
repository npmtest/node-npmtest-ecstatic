# npmtest-ecstatic

#### basic test coverage for  [ecstatic (v2.1.0)](https://github.com/jfhbrook/node-ecstatic)  [![npm package](https://img.shields.io/npm/v/npmtest-ecstatic.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ecstatic) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ecstatic.svg)](https://travis-ci.org/npmtest/node-npmtest-ecstatic)

#### A simple static file server middleware that works with both Express and Flatiron

[![NPM](https://nodei.co/npm/ecstatic.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ecstatic)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ecstatic/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ecstatic/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ecstatic/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ecstatic/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ecstatic/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ecstatic/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ecstatic/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ecstatic/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ecstatic/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ecstatic/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ecstatic/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ecstatic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ecstatic/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ecstatic/build/test-report.html](https://npmtest.github.io/node-npmtest-ecstatic/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ecstatic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ecstatic/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ecstatic/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ecstatic/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ecstatic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ecstatic/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ecstatic/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ecstatic/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joshua Holbrook",
        "url": "http://jesusabdullah.net"
    },
    "bin": {
        "ecstatic": "./lib/ecstatic.js"
    },
    "bugs": {
        "url": "https://github.com/jfhbrook/node-ecstatic/issues"
    },
    "dependencies": {
        "he": "^0.5.0",
        "mime": "^1.2.11",
        "minimist": "^1.1.0",
        "url-join": "^1.0.0"
    },
    "description": "A simple static file server middleware that works with both Express and Flatiron",
    "devDependencies": {
        "codecov": "^1.0.1",
        "eol": "^0.2.0",
        "express": "^4.12.3",
        "mkdirp": "^0.5.0",
        "request": "^2.49.0",
        "tap": "^5.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "477a4a6b25cecb112f697dbd2c7fa354154ea6be",
        "tarball": "https://registry.npmjs.org/ecstatic/-/ecstatic-2.1.0.tgz"
    },
    "gitHead": "a5e646b1122e51d715d03f3373a3ff99de84a9fc",
    "homepage": "https://github.com/jfhbrook/node-ecstatic",
    "keywords": [
        "static",
        "web",
        "server",
        "files",
        "mime",
        "middleware"
    ],
    "license": "MIT",
    "main": "./lib/ecstatic.js",
    "maintainers": [
        {
            "name": "jesusabdullah"
        },
        {
            "name": "jfhbrook"
        }
    ],
    "name": "ecstatic",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/jfhbrook/node-ecstatic.git"
    },
    "scripts": {
        "posttest": "tap --coverage-report=text-lcov | codecov",
        "test": "tap --coverage test/*.js"
    },
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

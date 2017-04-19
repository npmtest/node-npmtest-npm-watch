# npmtest-npm-watch

#### test coverage for  [npm-watch (v0.1.8)](https://github.com/grncdr/npm-watch)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-watch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-watch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-watch.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-watch)

#### run scripts from package.json when files change

[![NPM](https://nodei.co/npm/npm-watch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-watch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-watch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-watch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-watch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-watch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-watch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-watch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-watch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npm-watch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npm-watch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-watch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npm-watch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npm-watch/build/test-report.html](https://npmtest.github.io/node-npmtest-npm-watch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm-watch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm-watch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npm-watch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-watch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-watch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-watch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm-watch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm-watch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stephen Sugden"
    },
    "bin": {
        "npm-watch": "./cli.js"
    },
    "bugs": {
        "url": "git://github.com/grncdr/npm-watch/issues"
    },
    "dependencies": {
        "nodemon": "^1.3.8",
        "through2": "^2.0.0"
    },
    "description": "run scripts from package.json when files change",
    "devDependencies": {
        "crlf": "^1.1.0",
        "markdown-code-blocks": "0.0.1",
        "tape": "~2.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "18caddb1f769e21c896e6ba79168aed8e0da7eb8",
        "tarball": "https://registry.npmjs.org/npm-watch/-/npm-watch-0.1.8.tgz"
    },
    "gitHead": "fb34eea74c6dd932ab5cd5527026d386cdbf90c8",
    "homepage": "https://github.com/grncdr/npm-watch",
    "keywords": [
        "npm",
        "watch",
        "nodemon",
        "monitor"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "grncdr"
        },
        {
            "name": "jackwanders"
        },
        {
            "name": "moos"
        },
        {
            "name": "mordzuber"
        }
    ],
    "name": "npm-watch",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/grncdr/npm-watch.git"
    },
    "scripts": {
        "demo": "markdown-code-blocks -t bash < README.md",
        "exclusions": "bash -c echo 'An extension'",
        "prepublish": "crlf --set=LF cli.js watch-package.js"
    },
    "version": "0.1.8",
    "watch": {
        "test": [
            "watch-package.js",
            "test/*.js"
        ],
        "exclusions": {
            "patterns": "*",
            "extensions": "nothing",
            "ignore": "ignored.js"
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

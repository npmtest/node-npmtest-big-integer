# npmtest-big-integer

#### basic test coverage for  [big-integer (v1.6.21)](https://github.com/peterolson/BigInteger.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-big-integer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-big-integer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-big-integer.svg)](https://travis-ci.org/npmtest/node-npmtest-big-integer)

#### An arbitrary length integer library for Javascript

[![NPM](https://nodei.co/npm/big-integer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/big-integer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-big-integer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-big-integer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-big-integer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-big-integer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-big-integer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-big-integer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-big-integer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-big-integer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-big-integer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-big-integer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-big-integer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-big-integer/build/test-report.html](https://npmtest.github.io/node-npmtest-big-integer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-big-integer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-big-integer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-big-integer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-big-integer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-big-integer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-big-integer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-big-integer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-big-integer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Peter Olson"
    },
    "bin": {},
    "bugs": {
        "url": "https://github.com/peterolson/BigInteger.js/issues"
    },
    "contributors": [],
    "dependencies": {},
    "description": "An arbitrary length integer library for Javascript",
    "devDependencies": {
        "coveralls": "^2.11.4",
        "jasmine": "2.1.x",
        "jasmine-core": "^2.3.4",
        "karma": "^0.13.3",
        "karma-coverage": "^0.4.2",
        "karma-jasmine": "^0.3.6",
        "karma-phantomjs-launcher": "~0.1",
        "uglifyjs": "^2.4.10"
    },
    "directories": {},
    "dist": {
        "shasum": "ac7b4fd2d635d3cc7c337bf1bab9762e690e8e45",
        "tarball": "https://registry.npmjs.org/big-integer/-/big-integer-1.6.21.tgz"
    },
    "engines": {
        "node": ">=0.6"
    },
    "gitHead": "441ca6ed02655abc778beb0baf07259f6912018e",
    "homepage": "https://github.com/peterolson/BigInteger.js#readme",
    "keywords": [
        "math",
        "big",
        "bignum",
        "bigint",
        "biginteger",
        "integer",
        "arbitrary",
        "precision",
        "arithmetic"
    ],
    "license": "Unlicense",
    "main": "./BigInteger",
    "maintainers": [
        {
            "name": "peterolson"
        }
    ],
    "name": "big-integer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/peterolson/BigInteger.js.git"
    },
    "scripts": {
        "minify": "uglifyjs BigInteger.js -o BigInteger.min.js",
        "test": "karma start my.conf.js"
    },
    "version": "1.6.21"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-xmlbuilder

#### test coverage for  [xmlbuilder (v8.2.2)](http://github.com/oozcitak/xmlbuilder-js)  [![npm package](https://img.shields.io/npm/v/npmtest-xmlbuilder.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-xmlbuilder) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-xmlbuilder.svg)](https://travis-ci.org/npmtest/node-npmtest-xmlbuilder)

#### An XML builder for node.js

[![NPM](https://nodei.co/npm/xmlbuilder.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xmlbuilder)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-xmlbuilder/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-xmlbuilder/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-xmlbuilder/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-xmlbuilder/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-xmlbuilder/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-xmlbuilder/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-xmlbuilder/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-xmlbuilder/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-xmlbuilder/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-xmlbuilder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-xmlbuilder/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-xmlbuilder/build/test-report.html](https://npmtest.github.io/node-npmtest-xmlbuilder/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-xmlbuilder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-xmlbuilder/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-xmlbuilder/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-xmlbuilder/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xmlbuilder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xmlbuilder/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-xmlbuilder/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-xmlbuilder/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ozgur Ozcitak"
    },
    "bugs": {
        "url": "http://github.com/oozcitak/xmlbuilder-js/issues"
    },
    "contributors": [],
    "dependencies": {},
    "description": "An XML builder for node.js",
    "devDependencies": {
        "coffee-coverage": "*",
        "coffee-script": "*",
        "coveralls": "*",
        "istanbul": "*",
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "69248673410b4ba42e1a6136551d2922335aa773",
        "tarball": "https://registry.npmjs.org/xmlbuilder/-/xmlbuilder-8.2.2.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "gitHead": "ab5987b12bc06e4da8c37cd7fec8f93085d96d28",
    "homepage": "http://github.com/oozcitak/xmlbuilder-js",
    "keywords": [
        "xml",
        "xmlbuilder"
    ],
    "license": "MIT",
    "main": "./lib/index",
    "maintainers": [
        {
            "name": "oozcitak"
        }
    ],
    "name": "xmlbuilder",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/oozcitak/xmlbuilder-js.git"
    },
    "scripts": {
        "postpublish": "rm -rf lib",
        "prepublish": "coffee -co lib src",
        "test": "mocha && istanbul report text lcov"
    },
    "version": "8.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

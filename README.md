# npmtest-phridge

#### test coverage for  [phridge (v2.0.0)](https://github.com/peerigon/phridge#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-phridge.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-phridge) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-phridge.svg)](https://travis-ci.org/npmtest/node-npmtest-phridge)

#### A bridge between node and phantomjs

[![NPM](https://nodei.co/npm/phridge.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/phridge)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-phridge/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-phridge/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-phridge/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-phridge/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-phridge/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-phridge/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-phridge/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-phridge/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-phridge/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-phridge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-phridge/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-phridge/build/test-report.html](https://npmtest.github.io/node-npmtest-phridge/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-phridge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-phridge/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-phridge/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-phridge/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-phridge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-phridge/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-phridge/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-phridge/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "peerigon"
    },
    "bugs": {
        "url": "https://github.com/peerigon/phridge/issues"
    },
    "dependencies": {
        "fork-stream": "^0.0.4",
        "linerstream": "^0.1.4",
        "phantomjs-prebuilt": "^2.1.3",
        "temp": "^0.8.0"
    },
    "description": "A bridge between node and phantomjs",
    "devDependencies": {
        "chai": "^3.2.0",
        "chai-as-promised": "^5.1.0",
        "eslint": "^1.6.0",
        "eslint-config-peerigon": "^2.0.0",
        "getport": "^0.1.0",
        "istanbul": "^0.4.2",
        "mocha": "^2.2.5",
        "ps-node": "^0.0.5",
        "sinon": "^1.14.1",
        "sinon-chai": "^2.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "aba7392945242fb495277d70e76c4b97e4285bb6",
        "tarball": "https://registry.npmjs.org/phridge/-/phridge-2.0.0.tgz"
    },
    "gitHead": "0aa95f81dffcaab48357ebf2aab42ce64ce69247",
    "homepage": "https://github.com/peerigon/phridge#readme",
    "keywords": [
        "phantom",
        "phantomjs",
        "bridge",
        "driver"
    ],
    "license": "Unlicense",
    "main": "./lib/main.js",
    "maintainers": [
        {
            "name": "peerigon"
        }
    ],
    "name": "phridge",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/peerigon/phridge.git"
    },
    "scripts": {
        "coverage": "istanbul cover ./node_modules/mocha/bin/_mocha",
        "posttest": "eslint examples lib test",
        "test": "mocha -R spec"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

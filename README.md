# npmtest-usage

#### test coverage for  [usage (v0.7.1)](https://github.com/arunoda/node-usage)  [![npm package](https://img.shields.io/npm/v/npmtest-usage.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-usage) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-usage.svg)](https://travis-ci.org/npmtest/node-npmtest-usage)

#### simple way to lookup linux process usage

[![NPM](https://nodei.co/npm/usage.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/usage)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-usage/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-usage/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-usage/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-usage/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-usage/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-usage/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-usage/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-usage/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-usage/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-usage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-usage/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-usage/build/test-report.html](https://npmtest.github.io/node-npmtest-usage/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-usage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-usage/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-usage/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-usage/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-usage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-usage/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-usage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-usage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arunoda Susiripala"
    },
    "bugs": {
        "url": "https://github.com/arunoda/node-usage/issues"
    },
    "dependencies": {
        "bindings": "1.x.x",
        "nan": "^2.0.9"
    },
    "description": "simple way to lookup linux process usage",
    "devDependencies": {
        "mocha": "1.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "25f3106a519550aba41bf6e7685bc9bd533362ff",
        "tarball": "https://registry.npmjs.org/usage/-/usage-0.7.1.tgz"
    },
    "engines": {
        "node": ">= 0.10.x"
    },
    "gitHead": "6dcb60da3036812258f53400e0fc1a38ae25f82d",
    "gypfile": true,
    "homepage": "https://github.com/arunoda/node-usage",
    "keywords": [
        "usage",
        "ps",
        "cpu",
        "ram",
        "memory"
    ],
    "main": "./lib/usage.js",
    "maintainers": [
        {
            "name": "arunoda"
        }
    ],
    "name": "usage",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/arunoda/node-usage.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "mocha"
    },
    "version": "0.7.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-hippie [![npm package](https://img.shields.io/npm/v/npmtest-hippie.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hippie) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hippie.svg)](https://travis-ci.org/npmtest/node-npmtest-hippie)

test coverage for  [hippie (v0.5.1)](https://github.com/vesln/hippie)
#### Simple end-to-end API testing

[![NPM](https://nodei.co/npm/hippie.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hippie)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hippie/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hippie/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hippie/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hippie/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hippie/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hippie/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hippie/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hippie/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hippie/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hippie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hippie/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hippie/build/test-report.html](https://npmtest.github.io/node-npmtest-hippie/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hippie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hippie/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hippie/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hippie/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hippie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hippie/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hippie/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hippie/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Veselin Todorov"
    },
    "bugs": {
        "url": "https://github.com/vesln/hippie/issues"
    },
    "dependencies": {
        "assertion-error": "~1.0.0",
        "deep-eql": "~0.1.3",
        "es6-promise": "^3.0.2",
        "pathval": "0.0.1",
        "qs": "~0.6.5",
        "request": "~2.74.0"
    },
    "description": "Simple end-to-end API testing",
    "devDependencies": {
        "chai": "~1.8.1",
        "express": "~3.4.4",
        "hydro": "~0.8.7",
        "hydro-bdd": "~0.1.0",
        "hydro-chai": "~0.1.3",
        "hydro-clean-stacks": "~0.1.0",
        "hydro-dot": "~1.0.5",
        "istanbul": "~0.1.44",
        "jshint": "~2.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "050db4f3b6ee8daa8029abeba6b51e58b6cf1526",
        "tarball": "https://registry.npmjs.org/hippie/-/hippie-0.5.1.tgz"
    },
    "gitHead": "376c7e0985c599162e9f47ba7a33d1bfaa644760",
    "homepage": "https://github.com/vesln/hippie",
    "license": "MIT",
    "main": "./lib/hippie.js",
    "maintainers": [
        {
            "name": "cachecontrol"
        },
        {
            "name": "veselin"
        },
        {
            "name": "vesln"
        }
    ],
    "name": "hippie",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/vesln/hippie.git"
    },
    "scripts": {
        "coverage": "istanbul cover _hydro",
        "pretest": "jshint .",
        "test": "hydro"
    },
    "version": "0.5.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

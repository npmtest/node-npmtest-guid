# npmtest-guid

#### test coverage for  [guid (v0.0.12)](https://github.com/dandean/guid)  [![npm package](https://img.shields.io/npm/v/npmtest-guid.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-guid) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-guid.svg)](https://travis-ci.org/npmtest/node-npmtest-guid)

#### A Guid generator and validator.

[![NPM](https://nodei.co/npm/guid.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/guid)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-guid/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-guid/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-guid/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-guid/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-guid/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-guid/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-guid/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-guid/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-guid/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-guid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-guid/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-guid/build/test-report.html](https://npmtest.github.io/node-npmtest-guid/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-guid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-guid/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-guid/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-guid/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-guid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-guid/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-guid/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-guid/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dan Dean",
        "url": "http://dandean.com"
    },
    "bugs": {
        "url": "https://github.com/dandean/guid/issues"
    },
    "contributors": [
        {
            "name": "Tommy Messbauer"
        }
    ],
    "dependencies": {},
    "deprecated": "Please use node-uuid instead. It is much better.",
    "description": "A Guid generator and validator.",
    "devDependencies": {
        "mocha": "~1.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9137c52b185f7de12490b9bebcc1660b9025fe0c",
        "tarball": "https://registry.npmjs.org/guid/-/guid-0.0.12.tgz"
    },
    "ender": "./ender.js",
    "homepage": "https://github.com/dandean/guid",
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/dandean/guid/raw/master/LICENSE"
        }
    ],
    "main": "./guid",
    "maintainers": [
        {
            "name": "dandean"
        }
    ],
    "name": "guid",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dandean/guid.git"
    },
    "scripts": {
        "test": "mocha -R spec -u tdd tests/*.js"
    },
    "testling": {
        "browsers": {
            "ie": [
                6,
                7,
                8,
                9,
                10
            ],
            "ff": [
                24,
                25,
                "nightly"
            ],
            "chrome": [
                28,
                29,
                30,
                31,
                "canary"
            ],
            "safari": [
                "5.0.5",
                5.1
            ],
            "android-browser": [
                4.2
            ],
            "opera": [
                17,
                "next"
            ],
            "iphone": [
                6
            ],
            "ipad": [
                6
            ]
        },
        "harness": "mocha-tdd",
        "files": "tests/*.js"
    },
    "version": "0.0.12"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

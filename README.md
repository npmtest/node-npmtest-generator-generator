# npmtest-generator-generator

#### basic test coverage for  [generator-generator (v3.1.0)](https://github.com/yeoman/generator-generator#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-generator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-generator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-generator.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-generator)

#### Generate a Yeoman generator

[![NPM](https://nodei.co/npm/generator-generator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-generator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-generator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-generator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-generator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-generator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-generator/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-generator-generator/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-generator-generator/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-generator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-generator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-generator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-generator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-generator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-generator/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-generator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-generator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-generator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-generator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-generator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-generator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-generator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Yeoman team"
    },
    "bugs": {
        "url": "https://github.com/yeoman/generator-generator/issues"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "deep-extend": "^0.4.1",
        "generator-node": "^2.1.0",
        "inquirer-npm-name": "^2.0.0",
        "lodash": "^4.17.2",
        "mkdirp": "^0.5.1",
        "superb": "^1.3.0",
        "yeoman-generator": "^1.0.0",
        "yosay": "^2.0.0"
    },
    "description": "Generate a Yeoman generator",
    "devDependencies": {
        "coveralls": "^2.12.0",
        "eslint": "^3.18.0",
        "eslint-config-xo-space": "^0.16.0",
        "jest": "^19.0.2",
        "jest-cli": "^19.0.2",
        "nsp": "^2.6.3",
        "yeoman-assert": "^3.0.0",
        "yeoman-test": "^1.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "bdf3448e6d986e3a14116f93625bf7c0ca832023",
        "tarball": "https://registry.npmjs.org/generator-generator/-/generator-generator-3.1.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "eslintConfig": {
        "extends": "xo-space",
        "env": {
            "jest": true,
            "node": true
        }
    },
    "files": [
        "app",
        "subgenerator"
    ],
    "gitHead": "53272ca77bec1a08bef86ac84ef92bcbfd3cc6a3",
    "homepage": "https://github.com/yeoman/generator-generator#readme",
    "jest": {
        "testEnvironment": "node",
        "testPathIgnorePatterns": [
            "templates"
        ]
    },
    "keywords": [
        "yeoman-generator",
        "yeoman",
        "generator",
        "inception",
        "init",
        "create",
        "boilerplate"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "addyosmani"
        },
        {
            "name": "arthurvr"
        },
        {
            "name": "eddiemonge"
        },
        {
            "name": "mischah"
        },
        {
            "name": "passy"
        },
        {
            "name": "paulirish"
        },
        {
            "name": "sboudrias"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "generator-generator",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yeoman/generator-generator.git"
    },
    "scripts": {
        "prepublish": "nsp check",
        "pretest": "eslint . --fix",
        "test": "jest"
    },
    "version": "3.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

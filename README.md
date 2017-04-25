# npmtest-node-lambda

#### basic test coverage for  [node-lambda (v0.9.0)](https://github.com/rebelmail/node-lambda#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-node-lambda.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-lambda) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-lambda.svg)](https://travis-ci.org/npmtest/node-npmtest-node-lambda)

#### Command line tool for locally running and remotely deploying your node.js applications to Amazon Lambda.

[![NPM](https://nodei.co/npm/node-lambda.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-lambda)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-lambda/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-lambda/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-lambda/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-lambda/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-lambda/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node-lambda/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node-lambda/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-lambda/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-lambda/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-lambda/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-lambda/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-lambda/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-lambda/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-lambda/build/test-report.html](https://npmtest.github.io/node-npmtest-node-lambda/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-lambda/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-lambda/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-lambda/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-lambda/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-lambda/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-lambda/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-lambda/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-lambda/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "motdotla"
    },
    "bin": {
        "node-lambda": "./bin/node-lambda"
    },
    "bugs": {
        "url": "https://github.com/rebelmail/node-lambda/issues"
    },
    "dependencies": {
        "async": "^0.9.0",
        "aws-sdk": "^2.1.24",
        "commander": "^2.5.0",
        "dotenv": "^0.4.0",
        "fs-extra": "^0.30.0",
        "node-zip": "^1.1.0",
        "rimraf": "^2.2.8"
    },
    "description": "Command line tool for locally running and remotely deploying your node.js applications to Amazon Lambda.",
    "devDependencies": {
        "aws-sdk-mock": "^1.6.1",
        "chai": "^2.0.0",
        "hoek": "^2.11.1",
        "lodash": "^3.2.0",
        "mocha": "",
        "should": ""
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "b628257be2655caa674a5df1ec379e42a2b4467f",
        "tarball": "https://registry.npmjs.org/node-lambda/-/node-lambda-0.9.0.tgz"
    },
    "gitHead": "57400510481390fe775325fb20f537c42ae01bb8",
    "homepage": "https://github.com/rebelmail/node-lambda#readme",
    "keywords": [
        "lambda",
        "aws",
        "amazon",
        "amazon-lambda",
        "aws-lambda",
        "lambda-node",
        "deploy",
        "deployment"
    ],
    "license": "BSD-2-Clause",
    "main": "lib/main.js",
    "maintainers": [
        {
            "name": "deviavir"
        },
        {
            "name": "motdotla"
        }
    ],
    "name": "node-lambda",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/rebelmail/node-lambda.git"
    },
    "scripts": {
        "test": "mocha test/*.js"
    },
    "version": "0.9.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

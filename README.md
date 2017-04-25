# npmtest-slack-node

#### basic test coverage for  [slack-node (v0.1.8)](https://github.com/clonn/slack-node-sdk#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-slack-node.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-slack-node) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-slack-node.svg)](https://travis-ci.org/npmtest/node-npmtest-slack-node)

#### Slack API library for node

[![NPM](https://nodei.co/npm/slack-node.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/slack-node)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-slack-node/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-slack-node/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-slack-node/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-slack-node/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-slack-node/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-slack-node/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-slack-node/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-slack-node/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-slack-node/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-slack-node/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-slack-node/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-slack-node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-slack-node/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-slack-node/build/test-report.html](https://npmtest.github.io/node-npmtest-slack-node/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-slack-node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-slack-node/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-slack-node/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-slack-node/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-slack-node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-slack-node/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-slack-node/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-slack-node/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Caesar Chi"
    },
    "bugs": {
        "url": "https://github.com/clonn/slack-node-sdk/issues"
    },
    "dependencies": {
        "requestretry": "^1.2.2"
    },
    "description": "Slack API library for node",
    "devDependencies": {
        "coffee-script": "1.10.0",
        "mocha": "^2.1.0",
        "nock": "^1.2.0",
        "should": "~3.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "cda98de8681485b301dc6742ddc3897117fad349",
        "tarball": "https://registry.npmjs.org/slack-node/-/slack-node-0.1.8.tgz"
    },
    "gitHead": "059b89cb9e803be4185bedc0f90d17457fa3a413",
    "homepage": "https://github.com/clonn/slack-node-sdk#readme",
    "keywords": [
        "slack",
        "node",
        "sdk"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "clonn"
        },
        {
            "name": "kevinburke"
        }
    ],
    "name": "slack-node",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/clonn/slack-node-sdk.git"
    },
    "scripts": {
        "start": "coffee index.coffee",
        "test": "mocha ./lib/test"
    },
    "version": "0.1.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-fcm-node

#### basic test coverage for  [fcm-node (v1.2.0)](https://github.com/jlcvp/fcm-node)  [![npm package](https://img.shields.io/npm/v/npmtest-fcm-node.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fcm-node) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fcm-node.svg)](https://travis-ci.org/npmtest/node-npmtest-fcm-node)

#### A Node.JS simple interface to Google's Firebase Cloud Messaging (FCM). Supports both android and iOS, including topic messages, and parallel calls.
Aditionally it also keeps the callback behavior for the new firebase messaging service.

[![NPM](https://nodei.co/npm/fcm-node.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fcm-node)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fcm-node/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fcm-node/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fcm-node/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fcm-node/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fcm-node/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-fcm-node/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-fcm-node/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fcm-node/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fcm-node/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fcm-node/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fcm-node/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fcm-node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fcm-node/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fcm-node/build/test-report.html](https://npmtest.github.io/node-npmtest-fcm-node/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fcm-node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fcm-node/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fcm-node/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fcm-node/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fcm-node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fcm-node/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fcm-node/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fcm-node/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Leonardo Pereira"
    },
    "bugs": {
        "url": "https://github.com/jlcvp/fcm-node/issues"
    },
    "dependencies": {
        "firebase-admin": "^4.1.3",
        "mocha": "^3.2.0",
        "retry": "^0.9.0"
    },
    "description": "A Node.JS simple interface to Google's Firebase Cloud Messaging (FCM). Supports both android and iOS, including topic messages, and parallel calls.\nAditionally it also keeps the callback behavior for the new firebase messaging service.",
    "devDependencies": {},
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "56063f6ca5fa9192338ea2a71cb22704c6f30adc",
        "tarball": "https://registry.npmjs.org/fcm-node/-/fcm-node-1.2.0.tgz"
    },
    "gitHead": "6076cca5e99b03e2ee5c0226ee09dc4fc1ce21fd",
    "homepage": "https://github.com/jlcvp/fcm-node",
    "keywords": [
        "fcm",
        "gcm",
        "push",
        "notification",
        "push notification",
        "firebase",
        "firebase cloud messaging",
        "google",
        "android",
        "ios",
        "topic message",
        "parallel send"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jlcvp"
        }
    ],
    "name": "fcm-node",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jlcvp/fcm-node.git"
    },
    "scripts": {
        "debugtest": "mocha --debug-brk $npm_package_options_mocha",
        "test": "mocha"
    },
    "tonicExampleFilename": "example.js",
    "version": "1.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

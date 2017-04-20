# npmtest-react-native-meteor

#### basic test coverage for  [react-native-meteor (v1.0.3)](https://github.com/inProgress-team/react-native-meteor#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-native-meteor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-native-meteor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-native-meteor.svg)](https://travis-ci.org/npmtest/node-npmtest-react-native-meteor)

#### Full Meteor Client for React Native

[![NPM](https://nodei.co/npm/react-native-meteor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-native-meteor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-native-meteor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-meteor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-meteor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-native-meteor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-meteor/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-native-meteor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-native-meteor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-native-meteor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-native-meteor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-meteor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-native-meteor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-native-meteor/build/test-report.html](https://npmtest.github.io/node-npmtest-react-native-meteor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-native-meteor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-native-meteor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-native-meteor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-native-meteor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native-meteor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native-meteor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-native-meteor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-native-meteor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Théo Mathieu"
    },
    "bugs": {
        "url": "https://github.com/inProgress-team/react-native-meteor/issues"
    },
    "dependencies": {
        "base-64": "^0.1.0",
        "crypto-js": "^3.1.6",
        "ejson": "^2.1.2",
        "minimongo-cache": "0.0.48",
        "react-komposer": "^1.8.0",
        "react-mixin": "^3.0.3",
        "trackr": "^2.0.2",
        "underscore": "^1.8.3",
        "wolfy87-eventemitter": "^4.3.0"
    },
    "description": "Full Meteor Client for React Native",
    "devDependencies": {
        "babel-core": "^6.7.2",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-0": "^6.5.0",
        "chai": "^3.5.0",
        "mocha": "^2.4.5",
        "mock-socket": "^2.0.0",
        "sinon": "^1.17.3"
    },
    "directories": {},
    "dist": {
        "shasum": "335dc2e60ed941d968117eaeb06d2b5c8fb6a1e1",
        "tarball": "https://registry.npmjs.org/react-native-meteor/-/react-native-meteor-1.0.3.tgz"
    },
    "gitHead": "3d63517b65253c35348c9ad5fc51853b2fb2f9b2",
    "homepage": "https://github.com/inProgress-team/react-native-meteor#readme",
    "keywords": [
        "react-component",
        "ddp",
        "meteor",
        "react",
        "react-native",
        "ios",
        "android"
    ],
    "license": "MIT",
    "main": "src/Meteor.js",
    "maintainers": [
        {
            "name": "theo-mathieu"
        }
    ],
    "name": "react-native-meteor",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/inProgress-team/react-native-meteor.git"
    },
    "scripts": {
        "test": "mocha --compilers js:babel-core/register --require test/setup --recursive"
    },
    "version": "1.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

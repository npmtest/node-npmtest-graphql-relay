# npmtest-graphql-relay

#### basic test coverage for  [graphql-relay (v0.5.1)](https://github.com/graphql/graphql-relay-js)  [![npm package](https://img.shields.io/npm/v/npmtest-graphql-relay.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-graphql-relay) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-graphql-relay.svg)](https://travis-ci.org/npmtest/node-npmtest-graphql-relay)

#### A library to help construct a graphql-js server supporting react-relay.

[![NPM](https://nodei.co/npm/graphql-relay.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/graphql-relay)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-graphql-relay/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-graphql-relay/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-graphql-relay/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-graphql-relay/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-graphql-relay/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-graphql-relay/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-graphql-relay/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-graphql-relay/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-graphql-relay/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-graphql-relay/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-graphql-relay/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-graphql-relay/build/test-report.html](https://npmtest.github.io/node-npmtest-graphql-relay/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-graphql-relay/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-graphql-relay/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-graphql-relay/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-graphql-relay/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-graphql-relay/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-graphql-relay/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-graphql-relay/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-graphql-relay/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/graphql/graphql-relay-js/issues"
    },
    "contributors": [
        {
            "name": "Daniel Schafer"
        }
    ],
    "dependencies": {},
    "description": "A library to help construct a graphql-js server supporting react-relay.",
    "devDependencies": {
        "babel-cli": "^6.22.2",
        "babel-core": "^6.22.1",
        "babel-eslint": "^7.1.1",
        "babel-plugin-check-es2015-constants": "^6.22.0",
        "babel-plugin-syntax-async-functions": "6.13.0",
        "babel-plugin-transform-class-properties": "^6.22.0",
        "babel-plugin-transform-es2015-arrow-functions": "^6.22.0",
        "babel-plugin-transform-es2015-block-scoped-functions": "^6.22.0",
        "babel-plugin-transform-es2015-block-scoping": "^6.22.0",
        "babel-plugin-transform-es2015-classes": "^6.22.0",
        "babel-plugin-transform-es2015-computed-properties": "^6.22.0",
        "babel-plugin-transform-es2015-destructuring": "^6.22.0",
        "babel-plugin-transform-es2015-duplicate-keys": "^6.22.0",
        "babel-plugin-transform-es2015-function-name": "^6.22.0",
        "babel-plugin-transform-es2015-literals": "^6.22.0",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.22.0",
        "babel-plugin-transform-es2015-object-super": "^6.22.0",
        "babel-plugin-transform-es2015-parameters": "^6.22.0",
        "babel-plugin-transform-es2015-shorthand-properties": "^6.22.0",
        "babel-plugin-transform-es2015-spread": "^6.22.0",
        "babel-plugin-transform-es2015-template-literals": "^6.22.0",
        "babel-plugin-transform-flow-strip-types": "^6.22.0",
        "babel-plugin-transform-object-rest-spread": "^6.22.0",
        "babel-plugin-transform-regenerator": "^6.22.0",
        "chai": "3.5.0",
        "coveralls": "2.11.15",
        "eslint": "^3.14.1",
        "eslint-plugin-babel": "^4.0.1",
        "eslint-plugin-flowtype": "^2.30.0",
        "flow-bin": "^0.38.0",
        "graphql": "0.9.1",
        "isparta": "4.0.0",
        "mocha": "^3.2.0",
        "sane": "^1.5.0"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "3b3e44430a24c0f636e713f43f65bd542fe02ac9",
        "tarball": "https://registry.npmjs.org/graphql-relay/-/graphql-relay-0.5.1.tgz"
    },
    "files": [
        "lib",
        "README.md",
        "LICENSE",
        "PATENTS"
    ],
    "gitHead": "ea9c54e4b9538aeb6de3cf0ac2aa103964cfaa2a",
    "homepage": "https://github.com/graphql/graphql-relay-js",
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "dschafer"
        },
        {
            "name": "fb"
        },
        {
            "name": "josephsavona"
        },
        {
            "name": "kassens"
        },
        {
            "name": "leebyron"
        },
        {
            "name": "schrockn"
        },
        {
            "name": "steveluscher"
        },
        {
            "name": "wincent"
        },
        {
            "name": "yungsters"
        },
        {
            "name": "yuzhi"
        },
        {
            "name": "zpao"
        }
    ],
    "name": "graphql-relay",
    "optionalDependencies": {},
    "options": {
        "mocha": "src/**/__tests__/**/*.js"
    },
    "peerDependencies": {
        "graphql": "^0.5.0 || ^0.6.0 || ^0.7.0 || ^0.8.0-b || ^0.9.0"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/graphql/graphql-relay-js.git"
    },
    "scripts": {
        "build": "rm -rf lib/* && babel src --ignore __tests__ --out-dir lib",
        "check": "flow check",
        "cover": "babel-node node_modules/.bin/isparta cover --root src --report html node_modules/.bin/_mocha -- $npm_package_options_mocha",
        "cover:lcov": "babel-node node_modules/.bin/isparta cover --root src --report lcovonly node_modules/.bin/_mocha -- $npm_package_options_mocha",
        "lint": "eslint src",
        "prepublish": "./resources/prepublish.sh",
        "test": "npm run lint && npm run check && npm run testonly",
        "testonly": "babel-node ./node_modules/.bin/_mocha $npm_package_options_mocha",
        "watch": "babel-node scripts/watch.js"
    },
    "version": "0.5.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

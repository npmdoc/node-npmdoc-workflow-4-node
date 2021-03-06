# npmdoc-workflow-4-node

#### basic api documentation for  [workflow-4-node (v0.17.0)](https://github.com/unbornchikken/workflow-4-node)  [![npm package](https://img.shields.io/npm/v/npmdoc-workflow-4-node.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-workflow-4-node) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-workflow-4-node.svg)](https://travis-ci.org/npmdoc/node-npmdoc-workflow-4-node)

#### Workflow 4 Node is a .NET Workflow Foundation like framework for Node.js. The goal is to reach feature equivalence and beyond.

[![NPM](https://nodei.co/npm/workflow-4-node.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/workflow-4-node)

- [https://npmdoc.github.io/node-npmdoc-workflow-4-node/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-workflow-4-node/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-workflow-4-node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-workflow-4-node/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-workflow-4-node/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-workflow-4-node/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gabor Mezo"
    },
    "bugs": {
        "url": "https://github.com/unbornchikken/workflow-4-node/issues"
    },
    "dependencies": {
        "babel-polyfill": "^6.2.0",
        "backpack-node": "*",
        "better-assert": "*",
        "bluebird": "*",
        "date-utils": "1",
        "debug": "*",
        "lodash": "*",
        "node-proxy": "*",
        "node-uuid": "*",
        "timespan": "*"
    },
    "description": "Workflow 4 Node is a .NET Workflow Foundation like framework for Node.js. The goal is to reach feature equivalence and beyond.",
    "devDependencies": {
        "babel": "^6.1.18",
        "babel-preset-es2015": "^6.1.18",
        "gulp": "*",
        "gulp-babel": "^6.1.0",
        "gulp-sequence": "*",
        "gulp-sourcemaps": "*",
        "mocha": "*",
        "yargs": "^3.30.0"
    },
    "directories": {},
    "dist": {
        "shasum": "19742dbfe6be61feebfcfadec50e7113af9252d4",
        "tarball": "https://registry.npmjs.org/workflow-4-node/-/workflow-4-node-0.17.0.tgz"
    },
    "engines": [
        "node >=0.10.0",
        "iojs >=1.0.0"
    ],
    "gitHead": "dfb5c8ba1e7b104f46f8264e73826645107cabee",
    "homepage": "https://github.com/unbornchikken/workflow-4-node",
    "keywords": [
        "workflow",
        "statemachine",
        "stateful",
        "development",
        "developmenttool"
    ],
    "license": "LGPL-3.0",
    "main": "./lib",
    "maintainers": [
        {
            "name": "unbornchikken"
        }
    ],
    "name": "workflow-4-node",
    "optionalDependencies": {
        "node-proxy": "*"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/unbornchikken/workflow-4-node.git"
    },
    "scripts": {
        "compile": "gulp",
        "test": "mocha tests",
        "test-es5": "mocha tests --old"
    },
    "version": "0.17.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

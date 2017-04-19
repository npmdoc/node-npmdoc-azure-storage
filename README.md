# npmdoc-azure-storage

#### api documentation for  [azure-storage (v2.1.0)](http://github.com/Azure/azure-storage-node)  [![npm package](https://img.shields.io/npm/v/npmdoc-azure-storage.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-azure-storage) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-azure-storage.svg)](https://travis-ci.org/npmdoc/node-npmdoc-azure-storage)

#### Microsoft Azure Storage Client Library for Node.js

[![NPM](https://nodei.co/npm/azure-storage.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/azure-storage)

- [https://npmdoc.github.io/node-npmdoc-azure-storage/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-azure-storage/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-azure-storage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-azure-storage/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-azure-storage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-azure-storage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Microsoft Corporation"
    },
    "browser": {
        "fs": "browserify-fs"
    },
    "bugs": {
        "url": "http://github.com/Azure/azure-storage-node/issues"
    },
    "dependencies": {
        "browserify-mime": "~1.2.9",
        "extend": "~1.2.1",
        "json-edm-parser": "0.1.2",
        "md5.js": "1.3.4",
        "node-uuid": "~1.4.0",
        "readable-stream": "~2.0.0",
        "request": "~2.74.0",
        "underscore": "~1.4.4",
        "validator": "~3.22.2",
        "xml2js": "0.2.7",
        "xmlbuilder": "0.4.3"
    },
    "description": "Microsoft Azure Storage Client Library for Node.js",
    "devDependencies": {
        "batchflow": "0.4.0",
        "browserify": "^13.3.0",
        "browserify-fs": "^1.0.0",
        "coveralls": "^2.11.4",
        "factor-bundle": "^2.5.0",
        "grunt": "~0.4.2",
        "grunt-contrib-jshint": "~0.11.0",
        "grunt-devserver": "^0.6.0",
        "grunt-jsdoc": "~2.1.0",
        "grunt-mocha": "^0.4.12",
        "grunt-mocha-test": "^0.12.7",
        "grunt-nsp": "^2.3.1",
        "ink-docstrap": "^1.3.0",
        "istanbul": "^0.3.22",
        "jshint": ">= 2.1.4",
        "mocha": ">= 1.18.0",
        "mocha-lcov-reporter": "^1.0.0",
        "nock": "0.16",
        "nsp": "^2.2.0",
        "should": "1.2.x"
    },
    "directories": {},
    "dist": {
        "shasum": "7fc81246cd64b54cabced70b5138d7cc4571ea01",
        "tarball": "https://registry.npmjs.org/azure-storage/-/azure-storage-2.1.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.26"
    },
    "gitHead": "d84dff922ee0bfc593c6e27191d61f9774c3bbbd",
    "homepage": "http://github.com/Azure/azure-storage-node",
    "keywords": [
        "node",
        "azure",
        "storage"
    ],
    "license": "Apache-2.0",
    "main": "./lib/azure-storage.js",
    "maintainers": [
        {
            "name": "windowsazure"
        }
    ],
    "name": "azure-storage",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/Azure/azure-storage-node.git"
    },
    "scripts": {
        "check": "jshint lib && nsp check",
        "cover": "istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec -u bdd --no-timeouts --recursive test",
        "coveralls": "npm run cover && cat ./coverage/lcov.info | node ./node_modules/coveralls/bin/coveralls.js",
        "genjs": "node ./browser/bundle.js",
        "test": "jshint lib && nsp check && mocha --no-timeouts --recursive test"
    },
    "tags": [
        "azure",
        "storage",
        "sdk"
    ],
    "typings": "typings/azure-storage/azure-storage.d.ts",
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

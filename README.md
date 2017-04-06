# api documentation for  [check-dependencies (v1.0.1)](https://github.com/mgol/check-dependencies)  [![npm package](https://img.shields.io/npm/v/npmdoc-check-dependencies.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-check-dependencies) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-check-dependencies.svg)](https://travis-ci.org/npmdoc/node-npmdoc-check-dependencies)
#### Checks if currently installed npm/bower dependencies are installed in the exact same versions that are specified in package.json/bower.json

[![NPM](https://nodei.co/npm/check-dependencies.png?downloads=true)](https://www.npmjs.com/package/check-dependencies)

[![apidoc](https://npmdoc.github.io/node-npmdoc-check-dependencies/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-check-dependencies_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-check-dependencies/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-check-dependencies/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-check-dependencies/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michał Gołębiowski",
        "email": "m.goleb@gmail.com"
    },
    "bin": {
        "check-dependencies": "./bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/mgol/check-dependencies/issues"
    },
    "dependencies": {
        "bower-config": "^1.4.0",
        "chalk": "^1.1.3",
        "findup-sync": "^0.4.2",
        "lodash.camelcase": "^4.3.0",
        "minimist": "^1.2.0",
        "semver": "^5.3.0"
    },
    "description": "Checks if currently installed npm/bower dependencies are installed in the exact same versions that are specified in package.json/bower.json",
    "devDependencies": {
        "bluebird": "3.4.1",
        "bower": "1.7.9",
        "eslint-config-mgol": "0.0.27",
        "fs-extra": "0.30.0",
        "graceful-fs": "4.1.6",
        "grunt": "1.0.1",
        "grunt-cli": "1.2.0",
        "grunt-contrib-clean": "1.0.0",
        "grunt-contrib-copy": "1.0.0",
        "grunt-eslint": "19.0.0",
        "grunt-mocha-test": "0.12.7",
        "load-grunt-tasks": "3.5.2",
        "mocha": "3.0.2",
        "sinon": "1.17.5",
        "time-grunt": "1.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9e7f15822de20621ec6b9ffaabac4d588c3811b0",
        "tarball": "https://registry.npmjs.org/check-dependencies/-/check-dependencies-1.0.1.tgz"
    },
    "engines": {
        "node": ">=4.4 <5 || >=6.3"
    },
    "files": [
        "bin",
        "lib"
    ],
    "gitHead": "7e4ae26d56883b6fa971b70fab6cfe30816928ce",
    "homepage": "https://github.com/mgol/check-dependencies",
    "keywords": [
        "dependency",
        "packages",
        "modules",
        "dependencies"
    ],
    "license": "MIT",
    "main": "./lib/check-dependencies.js",
    "maintainers": [
        {
            "name": "m_gol",
            "email": "m.goleb@gmail.com"
        }
    ],
    "name": "check-dependencies",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mgol/check-dependencies.git"
    },
    "scripts": {
        "test": "grunt"
    },
    "version": "1.0.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module check-dependencies](#apidoc.module.check-dependencies)
1.  [function <span class="apidocSignatureSpan">check-dependencies.</span>sync (cfg, cb)](#apidoc.element.check-dependencies.sync)



# <a name="apidoc.module.check-dependencies"></a>[module check-dependencies](#apidoc.module.check-dependencies)

#### <a name="apidoc.element.check-dependencies.sync"></a>[function <span class="apidocSignatureSpan">check-dependencies.</span>sync (cfg, cb)](#apidoc.element.check-dependencies.sync)
- description and source-code
```javascript
(cfg, cb) => checkDependenciesHelper('sync', cfg, cb)
```
- example usage
```shell
...
        /* handle output */
    });
'''
The promise should never fail.

There is a synchronous alternative -- the following code:
'''js
var output = require('check-dependencies').sync(config);
'''
will assign to 'output' the same object that would otherwise be passed to the 'callback' in the asynchronous scenario.

The 'config' object may have the following fields:

#### packageManager
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

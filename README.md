# npmdoc-imdb-api

#### api documentation for  [imdb-api (v2.2.2)](https://github.com/worr/node-imdb-api)  [![npm package](https://img.shields.io/npm/v/npmdoc-imdb-api.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-imdb-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-imdb-api.svg)](https://travis-ci.org/npmdoc/node-npmdoc-imdb-api)

#### Queries unofficial imdb APIs to get movie and television information from imdb

[![NPM](https://nodei.co/npm/imdb-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/imdb-api)

- [https://npmdoc.github.io/node-npmdoc-imdb-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-imdb-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-imdb-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-imdb-api/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-imdb-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-imdb-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "William Orr",
        "url": "http://worrbase.com/"
    },
    "bugs": {
        "url": "https://github.com/worr/node-imdb-api/issues"
    },
    "dependencies": {
        "es6-promise": "^3.2.1",
        "request": "^2.74.0",
        "request-promise": "^4.1.1"
    },
    "description": "Queries unofficial imdb APIs to get movie and television information from imdb",
    "devDependencies": {
        "nock": "8.x.x",
        "nodeunit": "0.x.x",
        "tslint": "^3.15.1",
        "typescript": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "63055da8db2fae66c5c9da707dffa088c4f0ae52",
        "tarball": "https://registry.npmjs.org/imdb-api/-/imdb-api-2.2.2.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "gitHead": "aeea21c6815b2c07ca9831ca0ea7ecc03ae10275",
    "homepage": "https://github.com/worr/node-imdb-api",
    "keywords": [
        "imdb",
        "movies",
        "search",
        "tv",
        "television"
    ],
    "license": "MIT",
    "main": "lib/imdb.js",
    "maintainers": [
        {
            "name": "worr"
        }
    ],
    "name": "imdb-api",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/worr/node-imdb-api.git"
    },
    "scripts": {
        "build": "tsc -p .",
        "check": "npm run lint && npm run test",
        "clean": "rm -rf node_modules lib",
        "lint": "tslint --project tsconfig.json",
        "prepublish": "npm run build",
        "test": "nodeunit test"
    },
    "version": "2.2.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

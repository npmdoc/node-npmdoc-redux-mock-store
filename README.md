# npmdoc-redux-mock-store

#### api documentation for  [redux-mock-store (v1.2.3)](https://github.com/arnaudbenard/redux-mock-store#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-redux-mock-store.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-redux-mock-store) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-redux-mock-store.svg)](https://travis-ci.org/npmdoc/node-npmdoc-redux-mock-store)

#### A mock store for testing your redux async action creators and middleware

[![NPM](https://nodei.co/npm/redux-mock-store.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-mock-store)

- [https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arnaud Benard"
    },
    "bugs": {
        "url": "https://github.com/arnaudbenard/redux-mock-store/issues"
    },
    "dependencies": {},
    "description": "A mock store for testing your redux async action creators and middleware",
    "devDependencies": {
        "babel-cli": "^6.11.4",
        "babel-core": "^6.13.2",
        "babel-preset-es2015": "^6.13.2",
        "expect": "^1.12.2",
        "mocha": "^2.3.3",
        "redux": "^3.0.4",
        "redux-thunk": "^2.0.1",
        "rimraf": "^2.4.3",
        "sinon": "^1.17.2",
        "standard": "^7.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "1b3ad299da91cb41ba30d68e3b6f024475fb9e1b",
        "tarball": "https://registry.npmjs.org/redux-mock-store/-/redux-mock-store-1.2.3.tgz"
    },
    "gitHead": "65d143a6a3a3b882c57731731adfdcc0e9cac86a",
    "homepage": "https://github.com/arnaudbenard/redux-mock-store#readme",
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "arnaudbenard"
        },
        {
            "name": "dmitry-zaets"
        }
    ],
    "name": "redux-mock-store",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/arnaudbenard/redux-mock-store.git"
    },
    "scripts": {
        "lint": "standard src/*.js test/*.js",
        "prepublish": "rimraf lib && babel src --out-dir lib",
        "pretest": "npm run lint",
        "test": "mocha --compilers js:babel-core/register --reporter spec test/*.js"
    },
    "version": "1.2.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

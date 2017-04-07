# api documentation for  [redux-mock-store (v1.2.2)](https://github.com/arnaudbenard/redux-mock-store#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-redux-mock-store.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-redux-mock-store) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-redux-mock-store.svg)](https://travis-ci.org/npmdoc/node-npmdoc-redux-mock-store)
#### [![Circle CI](https://circleci.com/gh/arnaudbenard/redux-mock-store/tree/master.svg?style=svg)](https://circleci.com/gh/arnaudbenard/redux-mock-store/tree/master)

[![NPM](https://nodei.co/npm/redux-mock-store.png?downloads=true)](https://www.npmjs.com/package/redux-mock-store)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-redux-mock-store_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arnaud Benard",
        "email": "arnaudm.benard@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/arnaudbenard/redux-mock-store/issues"
    },
    "dependencies": {},
    "description": "[![Circle CI](https://circleci.com/gh/arnaudbenard/redux-mock-store/tree/master.svg?style=svg)](https://circleci.com/gh/arnaudbenard/redux-mock-store/tree/master)",
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
        "shasum": "38007dc38f12ca8d965c7521afee5ccacc234d03",
        "tarball": "https://registry.npmjs.org/redux-mock-store/-/redux-mock-store-1.2.2.tgz"
    },
    "gitHead": "d141a70729032c06022b5cf49020d3647cea2d10",
    "homepage": "https://github.com/arnaudbenard/redux-mock-store#readme",
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "arnaudbenard",
            "email": "arnaudbenard13@gmail.com"
        },
        {
            "name": "dmitry-zaets",
            "email": "dmitry.zaets@gmail.com"
        }
    ],
    "name": "redux-mock-store",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
    "version": "1.2.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module redux-mock-store](#apidoc.module.redux-mock-store)



# <a name="apidoc.module.redux-mock-store"></a>[module redux-mock-store](#apidoc.module.redux-mock-store)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

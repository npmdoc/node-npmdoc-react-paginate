# npmdoc-react-paginate

#### basic api documentation for  [react-paginate (v4.3.1)](https://github.com/AdeleD/react-paginate#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-paginate.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-paginate) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-paginate.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-paginate)

#### A ReactJS component that creates a pagination.

[![NPM](https://nodei.co/npm/react-paginate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-paginate)

- [https://npmdoc.github.io/node-npmdoc-react-paginate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-paginate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-paginate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-paginate/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-paginate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-paginate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Adèle Delamarche"
    },
    "bugs": {
        "url": "https://github.com/AdeleD/react-paginate/issues"
    },
    "dependencies": {
        "classnames": "^2.2.5",
        "react": "^15.0.0",
        "react-addons-create-fragment": "^15.0.0"
    },
    "description": "A ReactJS component that creates a pagination.",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-core": "^6.18.2",
        "babel-jest": "^17.0.2",
        "babel-loader": "^6.2.8",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-react": "^6.16.0",
        "babel-preset-stage-0": "^6.16.0",
        "express": "^4.14.0",
        "jest-cli": "^17.0.3",
        "jquery": "^3.1.1",
        "react-addons-test-utils": "^15.0.0",
        "react-dom": "^15.0.0",
        "react-hot-loader": "^1.3.1",
        "serve-static": "^1.11.1",
        "webpack": "^1.13.3",
        "webpack-dev-middleware": "^1.8.4",
        "webpack-dev-server": "^1.16.2"
    },
    "directories": {},
    "dist": {
        "shasum": "5f72eba26f0b911f649beb6af36bc4e0c6d3bc85",
        "tarball": "https://registry.npmjs.org/react-paginate/-/react-paginate-4.3.1.tgz"
    },
    "gitHead": "c41105d020c17b932f4f28a675ed05cb92650ba0",
    "homepage": "https://github.com/AdeleD/react-paginate#readme",
    "jest": {
        "transform": {
            ".*": "<rootDir>/node_modules/babel-jest"
        },
        "testPathDirs": [
            "__tests__"
        ],
        "unmockedModulePathPatterns": [
            "<rootDir>/node_modules/react",
            "<rootDir>/node_modules/react-dom",
            "<rootDir>/node_modules/react-addons-test-utils",
            "<rootDir>/node_modules/fbjs"
        ],
        "modulePathIgnorePatterns": [
            "<rootDir>/node_modules/"
        ]
    },
    "keywords": [
        "react-component",
        "paginate",
        "paginator",
        "pagination"
    ],
    "license": "MIT",
    "main": "./dist/index.js",
    "maintainers": [
        {
            "name": "adele"
        }
    ],
    "name": "react-paginate",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/AdeleD/react-paginate.git"
    },
    "scripts": {
        "demo": "webpack",
        "prepublish": "babel ./react_components --out-dir ./dist --source-maps --presets es2015,stage-0,react",
        "start": "webpack-dev-server --hot --inline",
        "test": "BABEL_JEST_STAGE=0 jest"
    },
    "version": "4.3.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

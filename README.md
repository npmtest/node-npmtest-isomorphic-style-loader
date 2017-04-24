# npmtest-isomorphic-style-loader

#### basic test coverage for  [isomorphic-style-loader (v2.0.0)](https://github.com/kriasoft/isomorphic-style-loader#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-isomorphic-style-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-isomorphic-style-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-isomorphic-style-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-isomorphic-style-loader)

#### Isomorphic CSS style loader for Webpack

[![NPM](https://nodei.co/npm/isomorphic-style-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/isomorphic-style-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-isomorphic-style-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-isomorphic-style-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-isomorphic-style-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-isomorphic-style-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-isomorphic-style-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-isomorphic-style-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-isomorphic-style-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kriasoft",
        "url": "http://www.kriasoft.com"
    },
    "babel": {
        "presets": [
            "react",
            "latest"
        ],
        "plugins": [
            "transform-runtime"
        ]
    },
    "bugs": {
        "url": "https://github.com/kriasoft/isomorphic-style-loader/issues"
    },
    "contributors": [
        {
            "name": "Konstantin Tarkus"
        },
        {
            "name": "Vladimir Kutepov"
        }
    ],
    "dependencies": {
        "babel-runtime": "^6.23.0",
        "hoist-non-react-statics": "^1.2.0",
        "loader-utils": "^1.1.0",
        "prop-types": "^15.5.8"
    },
    "description": "Isomorphic CSS style loader for Webpack",
    "devDependencies": {
        "babel-cli": "^6.24.1",
        "babel-core": "^6.24.1",
        "babel-eslint": "^7.2.2",
        "babel-plugin-transform-runtime": "^6.23.0",
        "babel-preset-latest": "^6.24.1",
        "babel-preset-react": "^6.24.1",
        "babel-register": "^6.24.1",
        "chai": "^3.5.0",
        "coveralls": "^2.13.0",
        "create-react-class": "^15.5.2",
        "eslint": "^3.19.0",
        "eslint-config-airbnb": "^14.1.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.10.3",
        "istanbul": "^1.1.0-alpha.1",
        "jsdom": "^9.12.0",
        "mocha": "^3.2.0",
        "react": "^15.5.4",
        "react-dom": "^15.5.4",
        "rimraf": "^2.6.1",
        "sinon": "^2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d4d41a5f88a045dcdb3c5b61a464912bc6c0d3dc",
        "tarball": "https://registry.npmjs.org/isomorphic-style-loader/-/isomorphic-style-loader-2.0.0.tgz"
    },
    "eslintConfig": {
        "parser": "babel-eslint",
        "extends": "airbnb",
        "env": {
            "browser": true
        },
        "rules": {
            "import/no-extraneous-dependencies": "off",
            "no-continue": "off",
            "no-plusplus": "off",
            "react/jsx-filename-extension": "off"
        }
    },
    "files": [
        "lib"
    ],
    "gitHead": "8fe56ef8fba794e00bfbc9b6d731edf0f572d4e7",
    "homepage": "https://github.com/kriasoft/isomorphic-style-loader#readme",
    "keywords": [
        "webpack",
        "webpack-loader",
        "webpack loader",
        "loader",
        "css",
        "scss",
        "style",
        "styles",
        "style-loader",
        "style loader",
        "react",
        "reactjs",
        "isomorphic",
        "universal"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "frenzzy"
        },
        {
            "name": "koistya"
        }
    ],
    "name": "isomorphic-style-loader",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kriasoft/isomorphic-style-loader.git"
    },
    "scripts": {
        "build": "rimraf lib && babel src --out-dir lib",
        "coveralls": "cat ./coverage/lcov.info | coveralls",
        "lint": "eslint src test",
        "prepublish": "rimraf lib && babel src --out-dir lib",
        "test": "mocha test --compilers js:babel-register",
        "test:cover": "babel-node ./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha",
        "test:watch": "mocha --compilers js:babel-register --reporter min --watch"
    },
    "version": "2.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

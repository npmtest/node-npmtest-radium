# npmtest-radium

#### test coverage for  [radium (v0.18.2)](https://github.com/formidablelabs/radium)  [![npm package](https://img.shields.io/npm/v/npmtest-radium.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-radium) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-radium.svg)](https://travis-ci.org/npmtest/node-npmtest-radium)

#### A set of tools to manage inline styles on React elements

[![NPM](https://nodei.co/npm/radium.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/radium)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-radium/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-radium/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-radium/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-radium/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-radium/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-radium/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-radium/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-radium/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-radium/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-radium/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-radium/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-radium/build/test-report.html](https://npmtest.github.io/node-npmtest-radium/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-radium/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-radium/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-radium/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-radium/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-radium/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-radium/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-radium/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-radium/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/formidablelabs/radium/issues"
    },
    "dependencies": {
        "array-find": "^1.0.0",
        "babel-cli": "^6.24.0",
        "babel-core": "^6.24.0",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-transform-decorators-legacy": "^1.3.4",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.24.0",
        "babel-preset-es2015": "^6.24.0",
        "babel-preset-react": "^6.23.0",
        "babel-preset-stage-1": "^6.22.0",
        "exenv": "^1.2.1",
        "inline-style-prefixer": "^2.0.5",
        "rimraf": "^2.6.1"
    },
    "description": "A set of tools to manage inline styles on React elements",
    "devDependencies": {
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.4.0",
        "chai": "^3.5.0",
        "color": "^1.0.3",
        "concurrently": "^3.4.0",
        "coveralls": "^2.12.0",
        "eslint": "^3.17.1",
        "eslint-plugin-flow-vars": "^0.5.0",
        "eslint-plugin-prettier": "^2.0.1",
        "eslint-plugin-react": "^6.10.0",
        "express": "^4.15.2",
        "express-http-proxy": "^0.11.0",
        "flow-bin": "^0.41.0",
        "in-publish": "^2.0.0",
        "inject-loader": "^3.0.0-beta4",
        "isparta-loader": "^2.0.0",
        "karma": "^1.5.0",
        "karma-babel-preprocessor": "^6.0.1",
        "karma-coverage": "^1.1.1",
        "karma-ie-launcher": "^1.0.0",
        "karma-mocha": "^1.3.0",
        "karma-mocha-reporter": "^2.2.2",
        "karma-phantomjs-launcher": "^1.0.4",
        "karma-phantomjs-shim": "^1.4.0",
        "karma-sinon-chai": "^1.2.4",
        "karma-webpack": "^2.0.3",
        "lodash.merge": "^4.6.0",
        "mocha": "^3.2.0",
        "node-libs-browser": "^2.0.0",
        "nodemon": "^1.11.0",
        "object-assign": "^4.1.1",
        "phantomjs-prebuilt": "^2.1.14",
        "prettier": "^0.22.0",
        "react": "^15.4.2",
        "react-addons-test-utils": "^15.4.2",
        "react-dom": "^15.4.2",
        "sinon": "^2.0.0",
        "sinon-chai": "^2.8.0",
        "webpack": "^2.2.1",
        "webpack-dev-server": "^2.4.2"
    },
    "directories": {
        "example": "examples"
    },
    "dist": {
        "shasum": "1e296966d0bcac6652085cbe84c7b8ed0196d7c1",
        "tarball": "https://registry.npmjs.org/radium/-/radium-0.18.2.tgz"
    },
    "gitHead": "310a376a985411c52c33f3283ccc2fff9057d11d",
    "homepage": "https://github.com/formidablelabs/radium",
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "alexlande"
        },
        {
            "name": "coopy"
        },
        {
            "name": "eastridge"
        },
        {
            "name": "formidable"
        },
        {
            "name": "ianobermiller"
        },
        {
            "name": "kylecesmat"
        },
        {
            "name": "tptee"
        }
    ],
    "name": "radium",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/formidablelabs/radium.git"
    },
    "scripts": {
        "babel": "rimraf lib && babel src/ -d lib/",
        "deps-fix": "babel-node ./npm-scripts/move-babel-to-dependencies.js",
        "deps-restore": "git checkout package.json",
        "dist": "webpack && webpack --config=webpack.config.minified.js",
        "eslint": "eslint src examples --ext .js --ext .jsx",
        "examples": "webpack-dev-server --config examples/webpack.config.js --no-info --content-base examples/",
        "fixlint": "npm run eslint -- --fix",
        "flow": "flow check",
        "lib": "npm run babel && rimraf lib/__tests__ lib/__mocks__",
        "lint": "npm run eslint && npm run flow",
        "postinstall": "cd lib || npm run lib",
        "postpublish": "npm run deps-restore",
        "prepublish": "npm run lib && npm run dist && not-in-publish || (npm test && npm run lint && npm run deps-fix)",
        "start": "babel-node examples/server.js",
        "test": "karma start",
        "test-coverage": "karma start karma.conf.coverage.js",
        "test-dev": "karma start --no-single-run --auto-watch",
        "test-ie": "karma start karma.conf.ie.js",
        "universal": "concurrently --kill-others \"npm start\" \"npm run examples\""
    },
    "version": "0.18.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

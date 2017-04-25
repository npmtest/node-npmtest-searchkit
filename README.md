# npmtest-searchkit

#### basic test coverage for  [searchkit (v0.10.1)](http://www.searchkit.co)  [![npm package](https://img.shields.io/npm/v/npmtest-searchkit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-searchkit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-searchkit.svg)](https://travis-ci.org/npmtest/node-npmtest-searchkit)

#### A suite of react components to help create a UI quickly for elasticsearch

[![NPM](https://nodei.co/npm/searchkit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/searchkit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-searchkit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-searchkit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-searchkit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-searchkit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-searchkit/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-searchkit/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-searchkit/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-searchkit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-searchkit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-searchkit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-searchkit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-searchkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-searchkit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-searchkit/build/test-report.html](https://npmtest.github.io/node-npmtest-searchkit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-searchkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-searchkit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-searchkit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-searchkit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-searchkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-searchkit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-searchkit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-searchkit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        {
            "name": "Joseph McElroy"
        },
        {
            "name": "Siavash Etemadieh"
        }
    ],
    "bugs": {
        "url": "https://github.com/searchkit/searchkit/issues"
    },
    "contributors": [
        {
            "name": "Gregory Potdevin"
        }
    ],
    "dependencies": {
        "axios": "^0.9.1",
        "bem-cn": "^1.2.2",
        "es6-promise": "^3.1.2",
        "history": "^2.1.1",
        "lodash": "4.6.1",
        "qs": "github:ssetem/qs",
        "rc-slider": "3.3.2",
        "react": "^0.14.7",
        "react-addons-update": "^0.14.7"
    },
    "description": "A suite of react components to help create a UI quickly for elasticsearch ",
    "devDependencies": {
        "autoprefixer": "^6.3.3",
        "chalk": "^1.1.1",
        "css-loader": "^0.23.1",
        "ejs": "^2.4.1",
        "enzyme": "^2.0.0",
        "express": "^4.13.4",
        "extract-text-webpack-plugin": "^1.0.1",
        "file-loader": "^0.8.5",
        "html-webpack-plugin": "^2.9.0",
        "imports-loader": "^0.6.5",
        "istanbul": "^0.4.2",
        "istanbul-instrumenter-loader": "^0.2.0",
        "jasmine-ajax": "^3.2.0",
        "jasmine-core": "^2.3.4",
        "js-beautify": "^1.5.10",
        "json-loader": "^0.5.4",
        "karma": "^0.13.21",
        "karma-coverage": "^0.5.4",
        "karma-coveralls": "^1.1.2",
        "karma-jasmine": "^0.3.6",
        "karma-jasmine-diff-reporter": "^0.3.4",
        "karma-junit-reporter": "^0.3.8",
        "karma-phantomjs-launcher": "^1.0.0",
        "karma-sourcemap-loader": "^0.3.6",
        "karma-webpack": "^1.7.0",
        "method-override": "^2.3.5",
        "node-sass": "^3.4.2",
        "node-static": "^0.7.7",
        "null-loader": "^0.1.1",
        "phantomjs-polyfill": "0.0.2",
        "phantomjs-prebuilt": "^2.1.4",
        "postcss-loader": "^0.8.2",
        "protractor": "^3.2.1",
        "react-addons-test-utils": "^0.14.6",
        "react-dom": "^0.14.6",
        "react-router": "^2.4.0",
        "sass-loader": "^3.1.2",
        "serve-favicon": "^2.3.0",
        "sinon": "^1.17.2",
        "style-loader": "^0.13.0",
        "ts-loader": "^0.8.1",
        "ts-node": "^0.5.5",
        "typescript": "^1.8.7",
        "webpack": "^1.12.14",
        "webpack-config": "^4.0.0",
        "webpack-hot-middleware": "^2.9.1",
        "xenon": "^0.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "6fdf3ec400498408625bb6c3805ab91e99f775b1",
        "tarball": "https://registry.npmjs.org/searchkit/-/searchkit-0.10.1.tgz"
    },
    "gitHead": "f59f28398928c47ef0ec3b25706c224b008766b5",
    "homepage": "http://www.searchkit.co",
    "keywords": [
        "elasticsearch",
        "elastic search",
        "react",
        "ui components",
        "search",
        "library",
        "client-side",
        "widgets",
        "react components",
        "react-component"
    ],
    "license": "Apache-2.0",
    "main": "lib/src/index.js",
    "maintainers": [
        {
            "name": "phoey1"
        },
        {
            "name": "ssetem"
        }
    ],
    "name": "searchkit",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/searchkit/searchkit.git"
    },
    "scripts": {
        "build": "tsc; ./node_modules/.bin/webpack; rm release/ignore.js",
        "build:watch": "tsc -w",
        "prepublish": "rm -rf lib; rm -rf release; npm run-script build;",
        "test": "karma start --single-run --reporters progress,junit,coverage",
        "test:e2e": "protractor test/e2e/conf/protractor.conf.js",
        "test:e2e-standalone": "protractor test/e2e/conf/protractor.standalone.conf.js",
        "test:serve": "node test/e2e/server/start.js",
        "test:watch": "karma start karma.conf.js --auto-watch"
    },
    "typings": "lib/src/index.d.ts",
    "version": "0.10.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

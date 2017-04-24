# npmtest-c3

#### basic test coverage for  c3 (v0.4.11)  [![npm package](https://img.shields.io/npm/v/npmtest-c3.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-c3) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-c3.svg)](https://travis-ci.org/npmtest/node-npmtest-c3)

#### D3-based reusable chart library

[![NPM](https://nodei.co/npm/c3.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/c3)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-c3/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-c3/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-c3/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-c3/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-c3/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-c3/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-c3/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-c3/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-c3/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-c3/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-c3/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-c3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-c3/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-c3/build/test-report.html](https://npmtest.github.io/node-npmtest-c3/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-c3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-c3/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-c3/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-c3/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-c3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-c3/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-c3/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-c3/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "c3",
    "version": "0.4.11",
    "description": "D3-based reusable chart library",
    "main": "c3.js",
    "scripts": {
        "lint": "grunt lint",
        "test": "karma start karma.conf.js",
        "codecov": "cat coverage/*/lcov.info | codecov"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/masayuki0812/c3.git"
    },
    "keywords": [
        "d3",
        "chart",
        "graph"
    ],
    "author": "Masayuki Tanaka",
    "license": "MIT",
    "gitHead": "84e03109d9a590f9c8ef687c03d751f666080c6f",
    "readmeFilename": "README.md",
    "dependencies": {
        "d3": "~3.5.0"
    },
    "devDependencies": {
        "codecov.io": "^0.1.6",
        "grunt": "^0.4.5",
        "grunt-contrib-concat": "~0.5.0",
        "grunt-contrib-cssmin": "^0.10.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-uglify": "~0.4.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-karma": "^0.12.1",
        "grunt-sass": "^1.0.0",
        "jasmine-core": "^2.3.4",
        "jshint-stylish": "^2.1.0",
        "karma": "^0.13.10",
        "karma-coverage": "^0.5.2",
        "karma-jasmine": "^0.3.6",
        "karma-phantomjs-launcher": "^0.2.1",
        "karma-spec-reporter": "0.0.20",
        "load-grunt-tasks": "~0.2.0",
        "phantomjs": "^1.9.18"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

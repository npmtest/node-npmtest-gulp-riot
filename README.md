# npmtest-gulp-riot

#### basic test coverage for  gulp-riot (v1.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-riot.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-riot) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-riot.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-riot)

#### gulp plugin for riot

[![NPM](https://nodei.co/npm/gulp-riot.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-riot)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-riot/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-riot/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-riot/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-riot/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-riot/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-riot/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-riot/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-riot/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-riot/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-riot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-riot/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-riot/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-riot/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-riot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-riot/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-riot/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-riot/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-riot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-riot/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-riot/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-riot/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-riot",
    "version": "1.1.0",
    "description": "gulp plugin for riot",
    "keywords": [
        "gulpplugin",
        "riot",
        "riotjs",
        "gulp"
    ],
    "main": "build/index.js",
    "scripts": {
        "test": "gulp test",
        "build": "gulp",
        "prepublish": "rm -rf build/ && gulp"
    },
    "author": {
        "name": "jigsaw",
        "url": "http://jgs.me"
    },
    "repository": {
        "url": "https://github.com/e-jigsaw/gulp-riot.git"
    },
    "license": "MIT",
    "dependencies": {
        "gulp-util": "3.0.8",
        "riot": "3.3.1",
        "through2": "2.0.3"
    },
    "devDependencies": {
        "gulp": "^3.9.1",
        "gulp-espower": "^1.1.0",
        "gulp-livescript": "^3.0.1",
        "gulp-mocha": "^3.0.1",
        "livescript": "^1.5.0",
        "power-assert": "^1.4.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

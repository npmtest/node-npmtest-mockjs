# npmtest-mockjs

#### basic test coverage for  [mockjs (v1.0.1-beta3)](http://mockjs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-mockjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mockjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mockjs.svg)](https://travis-ci.org/npmtest/node-npmtest-mockjs)

#### 生成随机数据 & 拦截 Ajax 请求

[![NPM](https://nodei.co/npm/mockjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mockjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mockjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mockjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mockjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mockjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mockjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mockjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mockjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mockjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mockjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mockjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mockjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mockjs/build/test-report.html](https://npmtest.github.io/node-npmtest-mockjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mockjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mockjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mockjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mockjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mockjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mockjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mockjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mockjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "nuysoft@gmail.com"
    },
    "bin": {
        "random": "bin/random"
    },
    "bugs": {
        "url": "https://github.com/nuysoft/Mock/issues"
    },
    "dependencies": {
        "commander": "*"
    },
    "description": "生成随机数据 & 拦截 Ajax 请求",
    "devDependencies": {
        "gulp": "^3.9.0",
        "gulp-connect": "*",
        "gulp-coveralls": "^0.1.4",
        "gulp-istanbul": "^0.10.3",
        "gulp-jshint": "^2.0.0",
        "gulp-mocha": "^2.2.0",
        "gulp-mocha-phantomjs": "^0.10.1",
        "jshint": "^2.8.0",
        "jshint-stylish": "^2.1.0",
        "webpack": "^1.12.9"
    },
    "directories": {},
    "dist": {
        "shasum": "d234f3c27256397564f2c955142e891909537209",
        "tarball": "https://registry.npmjs.org/mockjs/-/mockjs-1.0.1-beta3.tgz"
    },
    "gitHead": "c4d7cba01900b5c5bb8e3d474c8f5d07810ab72e",
    "homepage": "http://mockjs.com/",
    "keywords": [
        "mock",
        "mockJSON",
        "mockAjax"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/nuysoft/Mock/blob/master/LICENSE"
        }
    ],
    "main": "./dist/mock.js",
    "maintainers": [
        {
            "name": "nuysoft"
        }
    ],
    "name": "mockjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/nuysoft/Mock.git"
    },
    "scripts": {
        "coveralls": "gulp coveralls",
        "test": "gulp mocha"
    },
    "spm": {
        "main": "dist/mock.js"
    },
    "title": "Mock.js",
    "version": "1.0.1-beta3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

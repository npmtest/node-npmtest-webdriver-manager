# npmtest-webdriver-manager

#### basic test coverage for  webdriver-manager (v12.0.4)  [![npm package](https://img.shields.io/npm/v/npmtest-webdriver-manager.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webdriver-manager) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webdriver-manager.svg)](https://travis-ci.org/npmtest/node-npmtest-webdriver-manager)

#### A selenium server and browser driver manager for your end to end tests.

[![NPM](https://nodei.co/npm/webdriver-manager.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webdriver-manager)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webdriver-manager/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webdriver-manager/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webdriver-manager/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webdriver-manager/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webdriver-manager/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webdriver-manager/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webdriver-manager/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webdriver-manager/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webdriver-manager/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webdriver-manager/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webdriver-manager/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webdriver-manager/build/test-report.html](https://npmtest.github.io/node-npmtest-webdriver-manager/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webdriver-manager/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webdriver-manager/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webdriver-manager/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webdriver-manager/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webdriver-manager/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webdriver-manager/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webdriver-manager/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webdriver-manager/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "webdriver-manager",
    "version": "12.0.4",
    "description": "A selenium server and browser driver manager for your end to end tests.",
    "scripts": {
        "check_format": "gulp format:enforce",
        "format": "gulp format",
        "prepublish": "gulp prepublish",
        "test": "gulp test",
        "test_unit": "gulp test:unit",
        "test_circle_e2e": "gulp test:e2e:no_kvm"
    },
    "keywords": [
        "angular",
        "test",
        "testing",
        "protractor",
        "webdriver",
        "webdriverjs",
        "selenium",
        "selenium-webdriver"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/angular/webdriver-manager.git"
    },
    "bin": {
        "webdriver-manager": "bin/webdriver-manager"
    },
    "main": "built/lib/webdriver.js",
    "author": "Craig Nishina <craig.nishina@gmail.com>",
    "license": "MIT",
    "dependencies": {
        "adm-zip": "^0.4.7",
        "chalk": "^1.1.1",
        "del": "^2.2.0",
        "glob": "^7.0.3",
        "ini": "^1.3.4",
        "minimist": "^1.2.0",
        "q": "^1.4.1",
        "request": "^2.78.0",
        "rimraf": "^2.5.2",
        "semver": "^5.3.0",
        "xml2js": "^0.4.17"
    },
    "devDependencies": {
        "@types/adm-zip": "^0.4.29",
        "@types/chalk": "^0.4.28",
        "@types/form-data": "^0.0.33",
        "@types/glob": "^5.0.29",
        "@types/ini": "^1.3.28",
        "@types/jasmine": "^2.5.43",
        "@types/minimatch": "^2.0.28",
        "@types/minimist": "^1.1.28",
        "@types/node": "^7.0.4",
        "@types/q": "^0.0.32",
        "@types/request": "^0.0.39",
        "@types/rimraf": "^0.0.28",
        "@types/selenium-webdriver": "^2.53.35",
        "@types/semver": "^5.3.30",
        "@types/xml2js": "0.0.32",
        "clang-format": "^1.0.35",
        "gulp": "^3.9.1",
        "gulp-clang-format": "^1.0.23",
        "jasmine": "^2.4.1",
        "run-sequence": "^1.1.5",
        "selenium-webdriver": "~3.0.1",
        "typescript": "~2.2.0"
    },
    "engines": {
        "node": ">=6.9.x"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

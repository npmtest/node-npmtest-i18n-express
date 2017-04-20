# npmtest-i18n-express

#### basic test coverage for  [i18n-express (v1.1.2)](https://github.com/koalazak/i18n-express)  [![npm package](https://img.shields.io/npm/v/npmtest-i18n-express.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-i18n-express) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-i18n-express.svg)](https://travis-ci.org/npmtest/node-npmtest-i18n-express)

#### A simple i18n middleware for Express.js.

[![NPM](https://nodei.co/npm/i18n-express.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/i18n-express)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-i18n-express/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-i18n-express/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-i18n-express/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-i18n-express/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-i18n-express/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-i18n-express/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-i18n-express/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-i18n-express/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-i18n-express/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-i18n-express/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-i18n-express/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-i18n-express/build/test-report.html](https://npmtest.github.io/node-npmtest-i18n-express/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-i18n-express/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-i18n-express/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-i18n-express/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-i18n-express/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-i18n-express/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-i18n-express/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-i18n-express/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-i18n-express/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "i18n-express",
    "version": "1.1.2",
    "description": "A simple i18n middleware for Express.js.",
    "main": "index.js",
    "scripts": {
        "pretest": "npm install",
        "check:style": "eslint .",
        "test": "_mocha -- $npm_package_config_mocha && npm run check:style && npm run test:coverage",
        "test:coverage:run": "istanbul cover _mocha -- $npm_package_config_mocha",
        "test:coverage:check": "istanbul check-coverage --functions 80",
        "test:coverage": "npm run test:coverage:run && npm run test:coverage:check"
    },
    "devDependencies": {
        "mocha": "^3.1.2",
        "istanbul": "^0.4.0",
        "semistandard": "^9.1.0",
        "eslint": "^3.8.0",
        "eslint-config-standard": "^6.2.0",
        "eslint-config-semistandard": "^7.0.0",
        "eslint-plugin-promise": "^3.0.0",
        "eslint-plugin-standard": "^2.0.1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/koalazak/i18n-express.git"
    },
    "keywords": [
        "i18n",
        "express",
        "middleware",
        "json",
        "internationalisation",
        "node",
        "session",
        "language",
        "lang",
        "cookies",
        "javascript",
        "js",
        "handlebars",
        "ejs"
    ],
    "author": "koalazak <zak.tux@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/koalazak/i18n-express/issues"
    },
    "homepage": "https://github.com/koalazak/i18n-express"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

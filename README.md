# npmtest-manifestation

#### basic test coverage for  [manifestation (v2.0.9)](https://github.com/patrickkettner/manifestation#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-manifestation.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-manifestation) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-manifestation.svg)](https://travis-ci.org/npmtest/node-npmtest-manifestation)

#### Generate a Web App Manifest form your existing HTML

[![NPM](https://nodei.co/npm/manifestation.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/manifestation)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-manifestation/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-manifestation/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-manifestation/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-manifestation/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-manifestation/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-manifestation/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-manifestation/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-manifestation/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-manifestation/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-manifestation/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-manifestation/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-manifestation/build/test-report.html](https://npmtest.github.io/node-npmtest-manifestation/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-manifestation/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-manifestation/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-manifestation/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-manifestation/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-manifestation/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-manifestation/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-manifestation/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-manifestation/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "manifestation",
    "version": "2.0.9",
    "description": "Generate a Web App Manifest form your existing HTML",
    "main": "lib/index",
    "scripts": {
        "test": "npm run lint && npm run mocha",
        "lint": "eslint .",
        "mocha": "mocha ./test/**/*.js"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/patrickkettner/manifestation.git"
    },
    "keywords": [
        "web",
        "app",
        "manifest",
        "appmanifest"
    ],
    "author": "Patrick Kettner",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/patrickkettner/manifestation/issues"
    },
    "homepage": "https://github.com/patrickkettner/manifestation#readme",
    "dependencies": {
        "async": "^1.5.2",
        "cheerio": "^0.20.0",
        "cld": "^2.4.6",
        "eslint-config-hapi": "^9.1.0",
        "expect": "^1.20.1",
        "file-type": "^3.8.0",
        "icojs": "^0.4.0",
        "image-size": "^0.5.0",
        "image-type": "^2.1.0",
        "lodash": "^4.13.1",
        "mime-types": "^2.1.11",
        "request": "^2.72.0",
        "strip-combining-marks": "^0.1.0",
        "tld-extract": "^1.0.1",
        "valid-url": "^1.0.9",
        "xregexp": "^3.1.1"
    },
    "devDependencies": {
        "eslint": "^2.13.0",
        "eslint-plugin-hapi": "^4.0.0",
        "istanbul": "^1.0.0-alpha.2",
        "mocha": "^2.5.3",
        "sinon": "^1.17.4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

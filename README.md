# npmtest-jsreport

#### basic test coverage for  [jsreport (v1.7.0)](https://github.com/jsreport/jsreport)  [![npm package](https://img.shields.io/npm/v/npmtest-jsreport.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsreport) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsreport.svg)](https://travis-ci.org/npmtest/node-npmtest-jsreport)

#### javascript based business reporting

[![NPM](https://nodei.co/npm/jsreport.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsreport)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsreport/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsreport/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsreport/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsreport/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsreport/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsreport/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsreport/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jsreport/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jsreport/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsreport/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jsreport/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jsreport/build/test-report.html](https://npmtest.github.io/node-npmtest-jsreport/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsreport/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsreport/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jsreport/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsreport/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsreport/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsreport/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsreport/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsreport/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jsreport",
    "version": "1.7.0",
    "author": {
        "name": "Jan Blaha"
    },
    "contributors": [],
    "description": "javascript based business reporting",
    "keywords": [
        "report",
        "business",
        "javascript"
    ],
    "homepage": "https://github.com/jsreport/jsreport",
    "repository": {
        "type": "git",
        "url": "git@github.com:jsreport/jsreport.git"
    },
    "standard": {
        "ignore": [
            "data/**"
        ],
        "globals": [
            "describe",
            "it",
            "beforeEach",
            "define"
        ]
    },
    "jsreport": {
        "entryPoint": "server.js"
    },
    "dependencies": {
        "commander": "2.9.0",
        "cross-env": "2.0.1",
        "jsreport-assets": "0.6.5",
        "jsreport-authentication": "1.3.0",
        "jsreport-authorization": "1.1.1",
        "jsreport-browser-client": "1.2.1",
        "jsreport-child-templates": "0.4.4",
        "jsreport-cli": "1.2.2",
        "jsreport-core": "1.3.1",
        "jsreport-data": "1.1.2",
        "jsreport-debug": "1.0.5",
        "jsreport-express": "1.2.3",
        "jsreport-fop-pdf": "1.1.2",
        "jsreport-fs-store": "1.2.1",
        "jsreport-handlebars": "1.1.2",
        "jsreport-html-to-xlsx": "1.4.2",
        "jsreport-images": "1.1.1",
        "jsreport-import-export": "0.3.1",
        "jsreport-jsrender": "1.0.2",
        "jsreport-licensing": "1.2.1",
        "jsreport-phantom-pdf": "1.4.3",
        "jsreport-public-templates": "1.1.2",
        "jsreport-reports": "1.1.0",
        "jsreport-resources": "1.0.2",
        "jsreport-sample-template": "1.1.3",
        "jsreport-scheduling": "1.3.2",
        "jsreport-scripts": "1.4.2",
        "jsreport-studio": "1.5.3",
        "jsreport-tags": "1.0.2",
        "jsreport-templates": "1.1.1",
        "jsreport-text": "1.0.1",
        "jsreport-xlsx": "1.3.1",
        "mkdirp": "0.5.1",
        "node.extend": "1.1.6",
        "underscore": "1.8.3",
        "winston": "2.3.1"
    },
    "devDependencies": {
        "eslint": "3.19.0",
        "eslint-config-standard": "7.1.0",
        "eslint-config-standard-react": "4.3.0",
        "mocha": "3.2.0",
        "should": "11.2.1",
        "standard": "9.0.2"
    },
    "scripts": {
        "test": "mocha test --timeout 35000 && standard",
        "compile": "cross-env authentication_enabled=true jsreport-compile",
        "start": "node server.js"
    },
    "main": "index.js",
    "license": "LGPL",
    "files": [
        "lib",
        "example.config.json",
        "index.js",
        "config.md",
        "example.server.js"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

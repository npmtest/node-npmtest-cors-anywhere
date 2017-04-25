# npmtest-cors-anywhere

#### basic test coverage for  [cors-anywhere (v0.4.0)](https://github.com/Rob--W/cors-anywhere#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cors-anywhere.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cors-anywhere) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cors-anywhere.svg)](https://travis-ci.org/npmtest/node-npmtest-cors-anywhere)

#### CORS Anywhere is a reverse proxy which adds CORS headers to the proxied request. Request URL is taken from the path

[![NPM](https://nodei.co/npm/cors-anywhere.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cors-anywhere)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cors-anywhere/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cors-anywhere/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cors-anywhere/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cors-anywhere/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cors-anywhere/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-cors-anywhere/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-cors-anywhere/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cors-anywhere/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cors-anywhere/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cors-anywhere/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cors-anywhere/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cors-anywhere/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cors-anywhere/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cors-anywhere/build/test-report.html](https://npmtest.github.io/node-npmtest-cors-anywhere/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cors-anywhere/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cors-anywhere/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cors-anywhere/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cors-anywhere/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cors-anywhere/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cors-anywhere/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cors-anywhere/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cors-anywhere/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rob Wu"
    },
    "bugs": {
        "url": "https://github.com/Rob--W/cors-anywhere/issues/"
    },
    "dependencies": {
        "http-proxy": "1.11.1",
        "proxy-from-env": "0.0.1"
    },
    "description": "CORS Anywhere is a reverse proxy which adds CORS headers to the proxied request. Request URL is taken from the path",
    "devDependencies": {
        "coveralls": "^2.11.6",
        "eslint": "^2.2.0",
        "istanbul": "^0.4.2",
        "mocha": "~2.2.4",
        "nock": "~1.9.0",
        "supertest": "~0.15.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c3a2fd475bb304922ec29fbd6442e5adcf356b06",
        "tarball": "https://registry.npmjs.org/cors-anywhere/-/cors-anywhere-0.4.0.tgz"
    },
    "engines": {
        "node": ">=0.6.6",
        "npm": ">=1.1.0"
    },
    "gitHead": "3f4e9e093ce64f12853408f4383e19fa0975f091",
    "homepage": "https://github.com/Rob--W/cors-anywhere#readme",
    "keywords": [
        "cors",
        "cross-domain",
        "http-proxy",
        "proxy",
        "heroku"
    ],
    "license": "MIT",
    "main": "./lib/cors-anywhere.js",
    "maintainers": [
        {
            "name": "rob-w"
        }
    ],
    "name": "cors-anywhere",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Rob--W/cors-anywhere.git"
    },
    "scripts": {
        "lint": "eslint .",
        "start": "node server.js",
        "test": "mocha ./test/test*.js --reporter spec",
        "test-coverage": "istanbul cover ./node_modules/.bin/_mocha -- test/test.js --reporter spec"
    },
    "version": "0.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

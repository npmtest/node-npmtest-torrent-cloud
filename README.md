# npmtest-torrent-cloud

#### basic test coverage for  torrent-cloud (v0.1.2)  [![npm package](https://img.shields.io/npm/v/npmtest-torrent-cloud.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-torrent-cloud) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-torrent-cloud.svg)](https://travis-ci.org/npmtest/node-npmtest-torrent-cloud)

#### A torrent client in the cloud

[![NPM](https://nodei.co/npm/torrent-cloud.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/torrent-cloud)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-torrent-cloud/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-torrent-cloud/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-torrent-cloud/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-torrent-cloud/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-torrent-cloud/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-torrent-cloud/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-torrent-cloud/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-torrent-cloud/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-torrent-cloud/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-torrent-cloud/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-torrent-cloud/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-torrent-cloud/build/test-report.html](https://npmtest.github.io/node-npmtest-torrent-cloud/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-torrent-cloud/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-torrent-cloud/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-torrent-cloud/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-torrent-cloud/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-torrent-cloud/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-torrent-cloud/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-torrent-cloud/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-torrent-cloud/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "torrent-cloud",
    "version": "0.1.2",
    "description": "A torrent client in the cloud",
    "main": "server.js",
    "author": "Jaime Pillora <dev@jpillora.com>",
    "bin": {
        "torrent-cloud": "bin.js"
    },
    "license": "MIT",
    "dependencies": {
        "async": "^0.9.0",
        "aws-sdk": "^2.1.7",
        "basic-auth-connect": "^1.0.0",
        "body-parser": "^1.10.1",
        "cheerio": "^0.18.0",
        "express": "^4.11.0",
        "http-proxy": "^1.8.1",
        "mega": "^0.2.0",
        "mime": "^1.2.11",
        "mkdirp": "^0.5.0",
        "parse-torrent": "^4.0.0",
        "request": "^2.51.0",
        "rimraf": "^2.2.8",
        "torrent-stream": "^0.16.2",
        "ws": "^0.6.5",
        "zip-stream": "^0.5.0"
    },
    "engines": {
        "node": ">=0.10.x"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-events

#### basic test coverage for  [events (v1.1.1)](https://github.com/Gozala/events#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-events.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-events) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-events.svg)](https://travis-ci.org/npmtest/node-npmtest-events)

#### Node's event emitter for all engines.

[![NPM](https://nodei.co/npm/events.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/events)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-events/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-events/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-events/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-events/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-events/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-events/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-events/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-events/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-events/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-events/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-events/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-events/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-events/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-events/build/test-report.html](https://npmtest.github.io/node-npmtest-events/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-events/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-events/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-events/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-events/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-events/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-events/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-events/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-events/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Irakli Gozalishvili",
        "url": "http://jeditoolkit.com"
    },
    "bugs": {
        "url": "http://github.com/Gozala/events/issues/"
    },
    "dependencies": {},
    "description": "Node's event emitter for all engines.",
    "devDependencies": {
        "mocha": "~1.21.4",
        "zuul": "~1.10.2"
    },
    "directories": {},
    "dist": {
        "shasum": "9ebdb7635ad099c70dcc4c2a1f5004288e8bd924",
        "tarball": "https://registry.npmjs.org/events/-/events-1.1.1.tgz"
    },
    "engines": {
        "node": ">=0.4.x"
    },
    "gitHead": "623b6f54f3cdccedd71b8b0f5e4b755bacdb5c62",
    "homepage": "https://github.com/Gozala/events#readme",
    "id": "events",
    "keywords": [
        "events",
        "eventEmitter",
        "eventDispatcher",
        "listeners"
    ],
    "license": "MIT",
    "main": "./events.js",
    "maintainers": [
        {
            "name": "gozala"
        },
        {
            "name": "defunctzombie"
        }
    ],
    "name": "events",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Gozala/events.git",
        "web": "https://github.com/Gozala/events"
    },
    "scripts": {
        "test": "mocha --ui qunit -- tests/index.js && zuul -- tests/index.js"
    },
    "version": "1.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# test coverage for  [neo-async (v2.1.0)](https://github.com/suguru03/neo-async)  [![npm package](https://img.shields.io/npm/v/npmtest-neo-async.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-neo-async) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-neo-async.svg)](https://travis-ci.org/npmtest/node-npmtest-neo-async)
#### Neo-Async is thought to be used as a drop-in replacement for Async, it almost fully covers its functionality and runs faster

[![NPM](https://nodei.co/npm/neo-async.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/neo-async)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-neo-async/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-neo-async/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-neo-async/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-neo-async/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-neo-async/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-neo-async/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-neo-async/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-neo-async/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-neo-async/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-neo-async/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-neo-async/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-neo-async/build/test-report.html](https://npmtest.github.io/node-npmtest-neo-async/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-neo-async/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-neo-async/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-neo-async/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-neo-async/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-neo-async/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-neo-async/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-neo-async/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-neo-async/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/suguru03/neo-async/issues"
    },
    "dependencies": {},
    "description": "Neo-Async is thought to be used as a drop-in replacement for Async, it almost fully covers its functionality and runs faster ",
    "devDependencies": {
        "async": "git://github.com/caolan/async.git",
        "benchmark": "^2.1.1",
        "bluebird": "^3.4.7",
        "changelog-generator": "0.0.4",
        "codecov.io": "^0.1.6",
        "event-stream": "^3.3.3",
        "func-comparator": "^0.7.2",
        "gulp": "^3.9.1",
        "gulp-exit": "0.0.2",
        "gulp-git": "^1.10.0",
        "gulp-jsbeautifier": "^2.0.3",
        "gulp-jscs": "^4.0.0",
        "gulp-mocha": "^3.0.0",
        "gulp-util": "^3.0.7",
        "istanbul": "^0.4.3",
        "jsdoc": "^3.4.0",
        "jshint": "^2.9.2",
        "lodash": "^4.16.6",
        "minimist": "^1.2.0",
        "mocha": "^3.1.0",
        "mocha-parallel-executor": "^0.3.0",
        "mocha.parallel": "^0.15.0",
        "require-dir": "^0.3.0",
        "run-sequence": "^1.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "54e01a060b84b8731c62778b8aa9341892662c89",
        "tarball": "https://registry.npmjs.org/neo-async/-/neo-async-2.1.0.tgz"
    },
    "files": [
        "LICENSE",
        "CHANGELOG.md",
        "index.js",
        "lib/async.js",
        "lib/async.min.js",
        "dist/async.js",
        "dist/async.min.js"
    ],
    "gitHead": "45ac0fbaf38211bb0715077fc796244beb899fe7",
    "homepage": "https://github.com/suguru03/neo-async",
    "keywords": [
        "async",
        "util"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "suguru03"
        }
    ],
    "name": "neo-async",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/suguru03/neo-async.git"
    },
    "scripts": {
        "clean": "rm -rf coverage",
        "cov:100": "grep Lines | perl -nle 'my ($l, $c, $p, @d) = split(/[\\s%]+/); exit(($p == 100) == 0)'",
        "test": "istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- -R spec ./test --recursive"
    },
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

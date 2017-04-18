# npmtest-redis

#### test coverage for  [redis (v2.7.1)](https://github.com/NodeRedis/node_redis)  [![npm package](https://img.shields.io/npm/v/npmtest-redis.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-redis) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-redis.svg)](https://travis-ci.org/npmtest/node-npmtest-redis)

#### Redis client library

[![NPM](https://nodei.co/npm/redis.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redis)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-redis/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-redis/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-redis/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-redis/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-redis/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-redis/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-redis/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-redis/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-redis/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-redis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-redis/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-redis/build/test-report.html](https://npmtest.github.io/node-npmtest-redis/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-redis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-redis/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-redis/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redis/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redis/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-redis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-redis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt Ranney"
    },
    "bugs": {
        "url": "https://github.com/NodeRedis/node_redis/issues"
    },
    "dependencies": {
        "double-ended-queue": "^2.1.0-0",
        "redis-commands": "^1.2.0",
        "redis-parser": "^2.5.0"
    },
    "description": "Redis client library",
    "devDependencies": {
        "bluebird": "^3.0.2",
        "coveralls": "^2.11.2",
        "eslint": "^3.5.0",
        "intercept-stdout": "~0.1.2",
        "metrics": "^0.1.9",
        "mocha": "^3.1.2",
        "nyc": "^8.3.0",
        "tcp-port-used": "^0.1.2",
        "uuid": "^2.0.1",
        "win-spawn": "^2.0.0"
    },
    "directories": {
        "example": "examples",
        "test": "test"
    },
    "dist": {
        "shasum": "7d56f7875b98b20410b71539f1d878ed58ebf46a",
        "tarball": "https://registry.npmjs.org/redis/-/redis-2.7.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "5d73f5efa246f5f16f0e6ce2480fe4cdad8b0cb8",
    "homepage": "https://github.com/NodeRedis/node_redis",
    "keywords": [
        "database",
        "redis",
        "transaction",
        "pipelining",
        "performance",
        "queue",
        "nodejs",
        "pubsub",
        "backpressure"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "bcoe"
        },
        {
            "name": "bridgear"
        },
        {
            "name": "bryce"
        },
        {
            "name": "mjr"
        }
    ],
    "name": "redis",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/NodeRedis/node_redis.git"
    },
    "scripts": {
        "benchmark": "node benchmarks/multi_bench.js",
        "compare": "node benchmarks/diff_multi_bench_output.js beforeBench.txt afterBench.txt",
        "coverage": "nyc report --reporter=html",
        "coveralls": "nyc report --reporter=text-lcov | coveralls",
        "lint": "eslint . --fix && npm run coverage",
        "test": "nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000"
    },
    "version": "2.7.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

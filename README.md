# npmdoc-chalk

#### basic api documentation for  [chalk (v1.1.3)](https://github.com/chalk/chalk#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-chalk.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-chalk) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-chalk.svg)](https://travis-ci.org/npmdoc/node-npmdoc-chalk)

#### Terminal string styling done right. Much color.

[![NPM](https://nodei.co/npm/chalk.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/chalk)

- [https://npmdoc.github.io/node-npmdoc-chalk/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-chalk/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-chalk/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-chalk/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-chalk/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-chalk/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/chalk/chalk/issues"
    },
    "dependencies": {
        "ansi-styles": "^2.2.1",
        "escape-string-regexp": "^1.0.2",
        "has-ansi": "^2.0.0",
        "strip-ansi": "^3.0.0",
        "supports-color": "^2.0.0"
    },
    "description": "Terminal string styling done right. Much color.",
    "devDependencies": {
        "coveralls": "^2.11.2",
        "matcha": "^0.6.0",
        "mocha": "*",
        "nyc": "^3.0.0",
        "require-uncached": "^1.0.2",
        "resolve-from": "^1.0.0",
        "semver": "^4.3.3",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "a8115c55e4a702fe4d150abd3872822a7e09fc98",
        "tarball": "https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "0d8d8c204eb87a4038219131ad4d8369c9f59d24",
    "homepage": "https://github.com/chalk/chalk#readme",
    "keywords": [
        "color",
        "colour",
        "colors",
        "terminal",
        "console",
        "cli",
        "string",
        "str",
        "ansi",
        "style",
        "styles",
        "tty",
        "formatting",
        "rgb",
        "256",
        "shell",
        "xterm",
        "log",
        "logging",
        "command-line",
        "text"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "qix"
        },
        {
            "name": "sindresorhus"
        },
        {
            "name": "unicorn"
        }
    ],
    "name": "chalk",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/chalk/chalk.git"
    },
    "scripts": {
        "bench": "matcha benchmark.js",
        "coverage": "nyc npm test && nyc report",
        "coveralls": "nyc npm test && nyc report --reporter=text-lcov | coveralls",
        "test": "xo && mocha"
    },
    "version": "1.1.3",
    "xo": {
        "envs": [
            "node",
            "mocha"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

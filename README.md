# npmdoc-chalk

#### api documentation for  chalk (v1.1.3)  [![npm package](https://img.shields.io/npm/v/npmdoc-chalk.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-chalk) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-chalk.svg)](https://travis-ci.org/npmdoc/node-npmdoc-chalk)

#### Terminal string styling done right. Much color.

[![NPM](https://nodei.co/npm/chalk.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/chalk)

- [https://npmdoc.github.io/node-npmdoc-chalk/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-chalk/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-chalk/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-chalk/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-chalk/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-chalk/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "chalk",
    "version": "1.1.3",
    "description": "Terminal string styling done right. Much color.",
    "license": "MIT",
    "repository": "chalk/chalk",
    "maintainers": [
        "Sindre Sorhus <sindresorhus@gmail.com> (sindresorhus.com)",
        "Joshua Appelman <jappelman@xebia.com> (jbnicolai.com)",
        "JD Ballard <i.am.qix@gmail.com> (github.com/qix-)"
    ],
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "xo && mocha",
        "bench": "matcha benchmark.js",
        "coverage": "nyc npm test && nyc report",
        "coveralls": "nyc npm test && nyc report --reporter=text-lcov | coveralls"
    },
    "files": [
        "index.js"
    ],
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
    "dependencies": {
        "ansi-styles": "^2.2.1",
        "escape-string-regexp": "^1.0.2",
        "has-ansi": "^2.0.0",
        "strip-ansi": "^3.0.0",
        "supports-color": "^2.0.0"
    },
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
    "xo": {
        "envs": [
            "node",
            "mocha"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

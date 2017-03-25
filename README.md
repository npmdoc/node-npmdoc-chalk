# api documentation for  [chalk (v1.1.3)](https://github.com/chalk/chalk#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-chalk.svg)](https://travis-ci.org/npmdoc/node-npmdoc-chalk)
#### Terminal string styling done right. Much color.

[![NPM](https://nodei.co/npm/chalk.png?downloads=true)](https://www.npmjs.com/package/chalk)

[![apidoc](https://npmdoc.github.io/node-npmdoc-chalk/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-chalk_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-chalk/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-chalk/build/screen-capture.npmPackageListing.svg)



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
            "name": "qix",
            "email": "i.am.qix@gmail.com"
        },
        {
            "name": "sindresorhus",
            "email": "sindresorhus@gmail.com"
        },
        {
            "name": "unicorn",
            "email": "sindresorhus+unicorn@gmail.com"
        }
    ],
    "name": "chalk",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
    }
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module chalk](#apidoc.module.chalk)
1.  boolean <span class="apidocSignatureSpan">chalk.</span>enabled
1.  boolean <span class="apidocSignatureSpan">chalk.</span>supportsColor
1.  [function <span class="apidocSignatureSpan">chalk.</span>hasColor ()](#apidoc.element.chalk.hasColor)
1.  [function <span class="apidocSignatureSpan">chalk.</span>stripColor (str)](#apidoc.element.chalk.stripColor)
1.  object <span class="apidocSignatureSpan">chalk.</span>styles



# <a name="apidoc.module.chalk"></a>[module chalk](#apidoc.module.chalk)

#### <a name="apidoc.element.chalk.hasColor"></a>[function <span class="apidocSignatureSpan">chalk.</span>hasColor ()](#apidoc.element.chalk.hasColor)
- description and source-code
```javascript
hasColor = function () { [native code] }
```
- example usage
```shell
...

console.log(chalk.styles.red);
//=> {open: '\u001b[31m', close: '\u001b[39m'}

console.log(chalk.styles.red.open + 'Hello' + chalk.styles.red.close);
'''

### chalk.hasColor(string)

Check whether a string [has color](https://github.com/chalk/has-ansi).

### chalk.stripColor(string)

[Strip color](https://github.com/chalk/strip-ansi) from a string.
...
```

#### <a name="apidoc.element.chalk.stripColor"></a>[function <span class="apidocSignatureSpan">chalk.</span>stripColor (str)](#apidoc.element.chalk.stripColor)
- description and source-code
```javascript
stripColor = function (str) {
	return typeof str === 'string' ? str.replace(ansiRegex, '') : str;
}
```
- example usage
```shell
...
console.log(chalk.styles.red.open + 'Hello' + chalk.styles.red.close);
'''

### chalk.hasColor(string)

Check whether a string [has color](https://github.com/chalk/has-ansi).

### chalk.stripColor(string)

[Strip color](https://github.com/chalk/strip-ansi) from a string.

Can be useful in combination with '.supportsColor' to strip color on externally styled text when it's not supported.

Example:
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

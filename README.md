# npmdoc-chalk

#### basic api documentation for  [chalk (2.4.1)](https://github.com/chalk/chalk#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-chalk.svg)](https://travis-ci.org/npmdoc/node-npmdoc-chalk)

#### Terminal string styling done right

[![NPM](https://nodei.co/npm/chalk.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/chalk)

- [https://npmdoc.github.io/node-npmdoc-chalk/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-chalk/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-chalk/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-chalk/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-chalk/build/screenshot.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-chalk/build/screenshot.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/chalk/chalk/issues"
    },
    "dependencies": {
        "ansi-styles": "^3.2.1",
        "escape-string-regexp": "^1.0.5",
        "supports-color": "^5.3.0"
    },
    "description": "Terminal string styling done right",
    "devDependencies": {
        "ava": "*",
        "coveralls": "^3.0.0",
        "execa": "^0.9.0",
        "flow-bin": "^0.68.0",
        "import-fresh": "^2.0.0",
        "matcha": "^0.7.0",
        "nyc": "^11.0.2",
        "resolve-from": "^4.0.0",
        "typescript": "^2.5.3",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "integrity": "sha512-ObN6h1v2fTJSmUXoS3nMQ92LbDK9be4TV+6G+omQlGJFdcUX5heKi1LZ1YnRMIgwTLEj3E24bT6tYni50rlCfQ==",
        "shasum": "18c49ab16a037b6eb0152cc83e3471338215b66e",
        "tarball": "https://registry.npmjs.org/chalk/-/chalk-2.4.1.tgz",
        "fileCount": 7,
        "unpackedSize": 26917,
        "npm-signature": "-----BEGIN PGP SIGNATURE-----\r\nVersion: OpenPGP.js v3.0.4\r\nComment: https://openpgpjs.org\r\n\r\nwsFcBAEBCAAQBQJa4WCICRA9TVsSAnZWagAAhgwP/2M/ItinhR06BFhLMh91\nK/ru5t71NzSzoEvI2nh4W57Wk9cU1NOYi1cI17nUvICHCL4Vq9mjvU0hajTw\ncAYtM0Lwl+G4Hk4JtuiZITYj93QY3yLSJ8zkj95JznFbH0Zd9KkZrkoGukcG\nFY9at0cfNyhBmwi5sEDAFktcw7wThQ6Wy3iIttQ0N1M6Lf1XILg9Xyq6Id/W\nlz3TbkCt6AZCS1icmDPIiLdVQuD9SfpusIDsHm5/6FJPShwmQjUlM6Kdy7lx\n6M8uhcIknpxjfPTA6/aSBC4qgXnDhuPPi9xF657/81Mswz4Tb71KOf6UqLPi\n3zk1D5PF71ujWs3wmPll9TAVGnWuNzE+X/7GVIB4qCrib3SgvRzMhL0Wo95v\nzxTpNoD23hKYwofUyV3cTFh47YwkVoPtOStRAgdE87rx+v3VjbWSThQJc3V8\nHOsIeTjpQMwAr/d2DnasHKlps/q+gnGKqhBhcf11tAKn9C7PsAQ2l6+E4Erc\nfPKqDRC6TVG7ABdwOtyNonHhrJ2JLgYj8d4mHdtsMTtFsUTOQR/+Rx0V8HJS\n9gBLmPr3yc/yEedYW68wP5tPK2SfvFTzgMBw5v0+tgIxOjUunGxDUV4a1Bpp\npCBLN7iS77FLMiMonfcD2z/SsoB+Hb+7q5eT/gua3BIUNNZEdmgw9queXw+q\n7DFE\r\n=LSlF\r\n-----END PGP SIGNATURE-----\r\n"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "index.js",
        "templates.js",
        "types/index.d.ts",
        "index.js.flow"
    ],
    "gitHead": "48ba5b0b9beadcabd9fc406ac4d9337d8fa6b36d",
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
        "coveralls": "nyc report --reporter=text-lcov | coveralls",
        "test": "xo && tsc --project types && flow --max-warnings=0 && nyc ava"
    },
    "types": "types/index.d.ts",
    "version": "2.4.1",
    "xo": {
        "envs": [
            "node",
            "mocha"
        ],
        "ignores": [
            "test/_flow.js"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

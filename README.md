# npmdoc-gulp-print

#### basic api documentation for  [gulp-print (v2.0.1)](https://github.com/alexgorbatchev/gulp-print)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-print.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-print) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-print.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-print)

#### Prints names of files to the console so that you can see what's going through the the gulp pipe.

[![NPM](https://nodei.co/npm/gulp-print.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-print)

- [https://npmdoc.github.io/node-npmdoc-gulp-print/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-print/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-print/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-print/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-print/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-print/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alex Gorbatchev",
        "url": "https://github.com/alexgorbatchev"
    },
    "bugs": {
        "url": "https://github.com/alexgorbatchev/gulp-print/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.6",
        "map-stream": "~0.0.6"
    },
    "description": "Prints names of files to the console so that you can see what's going through the the gulp pipe.",
    "devDependencies": {
        "chai": "^3.2.0",
        "coffee-errors": "~0.8.6",
        "coffee-script": "~1.10.0",
        "mocha": "^2.3.2",
        "sinon": "^1.16.1",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1acee58eac8af2d3c4ad3329dbe465758393c414",
        "tarball": "https://registry.npmjs.org/gulp-print/-/gulp-print-2.0.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0",
        "npm": ">=1.2.10"
    },
    "gitHead": "2a47a249fb595ac3433f766ce03570d34b2506f3",
    "homepage": "https://github.com/alexgorbatchev/gulp-print",
    "keywords": [
        "gulpplugin",
        "log",
        "print",
        "debug",
        "status"
    ],
    "license": "MIT",
    "main": "./lib/gulp-print.js",
    "maintainers": [
        {
            "name": "alexgorbatchev"
        }
    ],
    "name": "gulp-print",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/alexgorbatchev/gulp-print.git"
    },
    "scripts": {
        "pretest": "coffee --bare --output ./lib --compile ./src/*.coffee",
        "test": "mocha test/*.spec.coffee"
    },
    "version": "2.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

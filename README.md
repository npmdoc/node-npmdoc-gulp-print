# api documentation for  [gulp-print (v2.0.1)](https://github.com/alexgorbatchev/gulp-print)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-print.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-print) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-print.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-print)
#### Prints names of files to the console so that you can see what's going through the the gulp pipe.

[![NPM](https://nodei.co/npm/gulp-print.png?downloads=true)](https://www.npmjs.com/package/gulp-print)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-print/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gulp-print_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-print/build/apidoc.html)

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
            "name": "alexgorbatchev",
            "email": "alex.gorbatchev@gmail.com"
        }
    ],
    "name": "gulp-print",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/alexgorbatchev/gulp-print.git"
    },
    "scripts": {
        "pretest": "coffee --bare --output ./lib --compile ./src/*.coffee",
        "test": "mocha test/*.spec.coffee"
    },
    "version": "2.0.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-print](#apidoc.module.gulp-print)
1.  [function <span class="apidocSignatureSpan">gulp-print.</span>log ()](#apidoc.element.gulp-print.log)



# <a name="apidoc.module.gulp-print"></a>[module gulp-print](#apidoc.module.gulp-print)

#### <a name="apidoc.element.gulp-print.log"></a>[function <span class="apidocSignatureSpan">gulp-print.</span>log ()](#apidoc.element.gulp-print.log)
- description and source-code
```javascript
log = function (){
  if(hasGulplog()){
    // specifically deferring loading here to keep from registering it globally
    var gulplog = require('gulplog');
    gulplog.info.apply(gulplog, arguments);
  } else {
    // specifically defering loading because it might not be used
    var fancylog = require('fancy-log');
    fancylog.apply(null, arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

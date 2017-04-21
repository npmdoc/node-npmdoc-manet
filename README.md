# npmdoc-manet

#### api documentation for  [manet (v0.4.19)](https://github.com/vbauer/manet)  [![npm package](https://img.shields.io/npm/v/npmdoc-manet.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-manet) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-manet.svg)](https://travis-ci.org/npmdoc/node-npmdoc-manet)

#### Website screenshot service powered by Node.js, SlimerJS and PhantomJS

[![NPM](https://nodei.co/npm/manet.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/manet)

- [https://npmdoc.github.io/node-npmdoc-manet/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-manet/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-manet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-manet/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-manet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-manet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "manet",
    "version": "0.4.19",
    "description": "Website screenshot service powered by Node.js, SlimerJS and PhantomJS",
    "license": "MIT",
    "repository": "vbauer/manet",
    "homepage": "https://github.com/vbauer/manet",
    "bugs": "https://github.com/vbauer/manet/issues",
    "main": "./src/runner.js",
    "bin": {
        "manet": "./bin/manet"
    },
    "author": {
        "name": "Vladislav Bauer",
        "url": "https://github.com/vbauer"
    },
    "keywords": [
        "screenshot",
        "thumbnail",
        "slimerjs",
        "slimer",
        "phantomjs",
        "phantom",
        "picture",
        "image",
        "website",
        "screen",
        "site",
        "page",
        "scr",
        "service",
        "server"
    ],
    "engines": {
        "node": ">=5.0.0",
        "npm": ">=3.0.0"
    },
    "scripts": {
        "lint": "jshint src test example public/js/app.js",
        "test": "mocha"
    },
    "dependencies": {
        "express": "^4.14.1",
        "request": "^2.79.0",
        "body-parser": "^1.16.1",
        "nocache": "^2.0.0",
        "passport": "^0.3.2",
        "passport-http": "^0.3.0",
        "fs-extra": "^2.0.0",
        "nconf": "^0.8.4",
        "js-yaml": "^3.8.1",
        "cloud-env": "^0.2.2",
        "joi": "^10.2.2",
        "qs": "^6.3.0",
        "lodash": "^4.17.4",
        "winston": "^2.3.1",
        "squirrel": "^1.0.0",
        "url-pattern": "^1.0.3"
    },
    "pluginDependencies": {
        "imagemin": "^3.2.2",
        "imagemin-gifsicle": "^4.2.0",
        "imagemin-jpegtran": "^4.3.1",
        "imagemin-optipng": "^4.3.0",
        "imagemin-svgo": "^4.1.2"
    },
    "devDependencies": {
        "jshint": "^2.9.4",
        "mocha": "^3.2.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

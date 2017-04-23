# npmtest-preload-webpack-plugin

#### basic test coverage for  [preload-webpack-plugin (v1.2.2)](https://github.com/googlechrome/preload-webpack-plugin)  [![npm package](https://img.shields.io/npm/v/npmtest-preload-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-preload-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-preload-webpack-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-preload-webpack-plugin)

#### Enhances html-webpack-plugin with link rel=preload wiring capabilities for scripts

[![NPM](https://nodei.co/npm/preload-webpack-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/preload-webpack-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-preload-webpack-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-preload-webpack-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-preload-webpack-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-preload-webpack-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-preload-webpack-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-preload-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-preload-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-preload-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Addy Osmani",
        "url": "https://github.com/addyosmani"
    },
    "bugs": {
        "url": "https://github.com/googlechrome/preload-webpack-plugin/issues"
    },
    "dependencies": {
        "object-assign": "^4.1.1"
    },
    "description": "Enhances html-webpack-plugin with link rel=preload wiring capabilities for scripts",
    "devDependencies": {
        "babel-eslint": "^7.1.1",
        "eslint": "^3.14.1",
        "eslint-config-google": "^0.7.1",
        "html-webpack-plugin": "^2.26.0",
        "jasmine": "^2.5.3",
        "webpack": "^2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d1b6f0eab3c2d0bb4c249d409cf6b7a8b0a415dd",
        "tarball": "https://registry.npmjs.org/preload-webpack-plugin/-/preload-webpack-plugin-1.2.2.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "be728dbfc1d55e778bae94ffb52389db9b936bc4",
    "homepage": "https://github.com/googlechrome/preload-webpack-plugin",
    "keywords": [
        "webpack",
        "plugin",
        "html-webpack-plugin",
        "script",
        "preload",
        "resource hints"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "addyosmani"
        }
    ],
    "name": "preload-webpack-plugin",
    "optionalDependencies": {},
    "peerDependencies": {
        "webpack": "^2.2.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/googlechrome/preload-webpack-plugin.git"
    },
    "scripts": {
        "lint": "eslint --quiet -f codeframe index.js test/spec.js",
        "lint-fix": "eslint --fix --quiet -f codeframe index.js test/spec.js",
        "test": "node_modules/jasmine/bin/jasmine.js test/spec.js"
    },
    "version": "1.2.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

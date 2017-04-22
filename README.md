# npmtest-paper

#### basic test coverage for  [paper (v0.11.2)](http://paperjs.org)  [![npm package](https://img.shields.io/npm/v/npmtest-paper.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-paper) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-paper.svg)](https://travis-ci.org/npmtest/node-npmtest-paper)

#### The Swiss Army Knife of Vector Graphics Scripting

[![NPM](https://nodei.co/npm/paper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/paper)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-paper/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-paper/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-paper/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-paper/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-paper/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-paper/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-paper/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-paper/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-paper/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-paper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-paper/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-paper/build/test-report.html](https://npmtest.github.io/node-npmtest-paper/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-paper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-paper/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-paper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-paper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-paper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-paper/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-paper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-paper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "canvas": false,
        "jsdom": false,
        "jsdom/lib/jsdom/living/generated/utils": false,
        "source-map-support": false,
        "./dist/node/self.js": false,
        "./dist/node/extend.js": false
    },
    "bugs": {
        "url": "https://github.com/paperjs/paper.js/issues"
    },
    "contributors": [
        {
            "name": "Jürg Lehni",
            "url": "http://scratchdisk.com"
        },
        {
            "name": "Jonathan Puckey",
            "url": "http://studiomoniker.com"
        }
    ],
    "dependencies": {},
    "description": "The Swiss Army Knife of Vector Graphics Scripting",
    "devDependencies": {
        "acorn": "~0.5.0",
        "canvas": "^1.3.5",
        "del": "^2.2.1",
        "gulp": "^3.9.1",
        "gulp-cached": "^1.1.0",
        "gulp-git-streamed": "^1.8.0",
        "gulp-jshint": "^2.0.0",
        "gulp-json-editor": "^2.2.1",
        "gulp-prepro": "^2.4.0",
        "gulp-qunits": "^2.1.1",
        "gulp-rename": "^1.2.2",
        "gulp-shell": "^0.5.2",
        "gulp-symlink": "^2.1.4",
        "gulp-uglify": "^1.5.4",
        "gulp-uncomment": "^0.3.0",
        "gulp-util": "^3.0.7",
        "gulp-webserver": "^0.9.1",
        "gulp-whitespace": "^0.1.0",
        "gulp-zip": "^3.2.0",
        "husky": "^0.11.4",
        "jsdom": "^9.4.0",
        "jshint": "^2.9.2",
        "jshint-summary": "^0.4.0",
        "merge-stream": "^1.0.0",
        "minimist": "^1.2.0",
        "prepro": "^2.4.0",
        "qunitjs": "^1.23.0",
        "require-dir": "^0.3.0",
        "resemblejs": "^2.2.1",
        "run-sequence": "^1.2.2",
        "source-map-support": "^0.4.0",
        "stats.js": "0.16.0",
        "straps": "^2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d016567eb1cbf7773cfad51a1a2cfd8c302f8b27",
        "tarball": "https://registry.npmjs.org/paper/-/paper-0.11.2.tgz"
    },
    "engines": {
        "node": ">=4.0.0 <8.0.0"
    },
    "files": [
        "AUTHORS.md",
        "CHANGELOG.md",
        "dist/",
        "examples/",
        "LICENSE.txt",
        "README.md"
    ],
    "gitHead": "db0d225df31c688a3fb7ef619bbba0c4c6bc05b3",
    "homepage": "http://paperjs.org",
    "keywords": [
        "vector",
        "graphic",
        "graphics",
        "2d",
        "geometry",
        "bezier",
        "curve",
        "curves",
        "path",
        "paths",
        "canvas",
        "svg",
        "paper",
        "paper.js",
        "paperjs"
    ],
    "license": "MIT",
    "main": "dist/paper-full.js",
    "maintainers": [
        {
            "name": "lehni"
        }
    ],
    "name": "paper",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/paperjs/paper.js.git"
    },
    "scripts": {
        "build": "gulp build",
        "dist": "gulp dist",
        "docs": "gulp docs",
        "jshint": "gulp jshint",
        "load": "gulp load",
        "precommit": "gulp jshint --branch develop",
        "prepush": "gulp test --branch develop",
        "test": "gulp test",
        "zip": "gulp zip"
    },
    "version": "0.11.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

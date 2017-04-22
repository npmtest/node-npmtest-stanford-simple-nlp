# npmtest-stanford-simple-nlp

#### basic test coverage for  stanford-simple-nlp (v0.2.2)  [![npm package](https://img.shields.io/npm/v/npmtest-stanford-simple-nlp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-stanford-simple-nlp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-stanford-simple-nlp.svg)](https://travis-ci.org/npmtest/node-npmtest-stanford-simple-nlp)

#### A simple node.js wrapper for Stanford CoreNLP.

[![NPM](https://nodei.co/npm/stanford-simple-nlp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stanford-simple-nlp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-stanford-simple-nlp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-stanford-simple-nlp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-stanford-simple-nlp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/test-report.html](https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-stanford-simple-nlp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stanford-simple-nlp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stanford-simple-nlp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stanford-simple-nlp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-stanford-simple-nlp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "stanford-simple-nlp",
    "version": "0.2.2",
    "author": {
        "name": "Taeho Kim"
    },
    "main": "index",
    "dependencies": {
        "coffee-script": "~1.7.1",
        "java": "~0.2.4",
        "xml2js": "~0.2.8"
    },
    "readmeFilename": "README.md",
    "description": "A simple node.js wrapper for Stanford CoreNLP.",
    "repository": {
        "type": "git",
        "url": "https://github.com/xissy/node-stanford-simple-nlp.git"
    },
    "bugs": {
        "url": "https://github.com/xissy/node-stanford-simple-nlp/issues"
    },
    "devDependencies": {
        "should": "~1.2.2",
        "mocha": "~1.12.0"
    },
    "directories": {
        "test": "test"
    },
    "scripts": {
        "test": "mocha --compilers coffee:coffee-script --require coffee-script/register --globals lw --recursive ./test -t 100000"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

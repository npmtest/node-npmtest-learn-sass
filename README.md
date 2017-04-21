# npmtest-learn-sass

#### basic test coverage for  [learn-sass (v1.3.1)](https://github.com/claudiopro/learn-sass#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-learn-sass.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-learn-sass) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-learn-sass.svg)](https://travis-ci.org/npmtest/node-npmtest-learn-sass)

#### Learn SASS and SCSS through a workshopper adventure.

[![NPM](https://nodei.co/npm/learn-sass.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/learn-sass)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-learn-sass/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-learn-sass/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-learn-sass/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-learn-sass/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-learn-sass/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-learn-sass/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-learn-sass/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-learn-sass/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-learn-sass/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-learn-sass/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-learn-sass/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-learn-sass/build/test-report.html](https://npmtest.github.io/node-npmtest-learn-sass/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-learn-sass/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-learn-sass/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-learn-sass/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-learn-sass/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-learn-sass/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-learn-sass/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-learn-sass/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-learn-sass/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "learn-sass",
    "version": "1.3.1",
    "description": "Learn SASS and SCSS through a workshopper adventure.",
    "main": "index.js",
    "scripts": {
        "lint": "sass-lint -v -o sass-lint.out",
        "test": "workshopper-adventure-test"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/claudiopro/learn-sass.git"
    },
    "keywords": [
        "sass",
        "css",
        "scss",
        "sassy",
        "workshopper",
        "adventure",
        "node",
        "nodejs",
        "nodeschool",
        "node-school"
    ],
    "bin": {
        "learn-sass": "./bin/learn-sass"
    },
    "author": {
        "name": "Claudio Procida",
        "url": "https://github.com/claudiopro"
    },
    "contributors": [
        "Claudio Procida <claudio.procida@gmail.com> (https://github.com/claudiopro)",
        "Nikolas Silva (https://github.com/nikolassilva)",
        "Martin Heidegger (https://github.com/martinheidegger)"
    ],
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/claudiopro/learn-sass/issues"
    },
    "homepage": "https://github.com/claudiopro/learn-sass#readme",
    "dependencies": {
        "after": "^0.8.2",
        "node-sass": "^4.1.0",
        "workshopper-adventure": "^5.1.6",
        "workshopper-exercise": "^2.7.0",
        "xtend": "^4.0.1"
    },
    "devDependencies": {
        "sass-lint": "^1.10.2",
        "workshopper-adventure-test": "^1.0.4"
    },
    "maintainers": [
        {
            "name": "Claudio Procida",
            "url": "https://github.com/claudiopro"
        },
        {
            "name": "Martin Heidegger",
            "url": "https://github.com/martinheidegger"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

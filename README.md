# npmtest-ember-metrics

#### basic test coverage for  [ember-metrics (v0.10.0)](https://github.com/poteto/ember-metrics)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-metrics.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-metrics) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-metrics.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-metrics)

#### Send data to multiple analytics integrations without re-implementing new API

[![NPM](https://nodei.co/npm/ember-metrics.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-metrics)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-metrics/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-metrics/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-metrics/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-metrics/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-metrics/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ember-metrics/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ember-metrics/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-metrics/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-metrics/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-metrics/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-metrics/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-metrics/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-metrics/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-metrics/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-metrics/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-metrics/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-metrics/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-metrics/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-metrics/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-metrics/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-metrics/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-metrics/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-metrics/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lauren Tan"
    },
    "bugs": {
        "url": "https://github.com/poteto/ember-metrics/issues"
    },
    "contributors": [
        {
            "name": "Michael Dupuis Jr"
        },
        {
            "name": "Mike North"
        }
    ],
    "dependencies": {
        "broccoli-funnel": "^1.0.1",
        "ember-cli-babel": "^5.1.6",
        "ember-getowner-polyfill": "^1.0.0",
        "ember-runtime-enumerable-includes-polyfill": "^1.0.1"
    },
    "description": "Send data to multiple analytics integrations without re-implementing new API",
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.2",
        "ember-ajax": "^2.0.1",
        "ember-cli": "2.7.0",
        "ember-cli-app-version": "^1.0.0",
        "ember-cli-dependency-checker": "^1.2.0",
        "ember-cli-htmlbars": "^1.0.3",
        "ember-cli-htmlbars-inline-precompile": "^0.3.1",
        "ember-cli-inject-live-reload": "^1.4.0",
        "ember-cli-jshint": "^1.0.0",
        "ember-cli-qunit": "^2.0.0",
        "ember-cli-release": "^0.2.9",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.5.1",
        "ember-resolver": "^2.0.3",
        "ember-sinon": "0.3.0",
        "loader.js": "^4.0.1"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "b3400aa8f001af5f39691266bea1d10b943c3cf6",
        "tarball": "https://registry.npmjs.org/ember-metrics/-/ember-metrics-0.10.0.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "ede0020bb01f059723396b74f64a28e63fd44cc8",
    "homepage": "https://github.com/poteto/ember-metrics",
    "keywords": [
        "ember-addon",
        "metrics",
        "analytics",
        "segment",
        "tracking",
        "google analytics",
        "google tag manager",
        "mixpanel",
        "piwik",
        "intercom",
        "facebook-pixel"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "sugarpirate"
        }
    ],
    "name": "ember-metrics",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/poteto/ember-metrics.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:each"
    },
    "version": "0.10.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

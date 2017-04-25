# npmtest-swagger-express-middleware

#### basic test coverage for  [swagger-express-middleware (v0.4.7)](https://github.com/BigstickCarpet/swagger-express-middleware)  [![npm package](https://img.shields.io/npm/v/npmtest-swagger-express-middleware.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-swagger-express-middleware) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-swagger-express-middleware.svg)](https://travis-ci.org/npmtest/node-npmtest-swagger-express-middleware)

#### Swagger middleware and mocks for Express

[![NPM](https://nodei.co/npm/swagger-express-middleware.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/swagger-express-middleware)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-swagger-express-middleware/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-swagger-express-middleware/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-swagger-express-middleware/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-swagger-express-middleware/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/test-report.html](https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-swagger-express-middleware/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-swagger-express-middleware/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swagger-express-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swagger-express-middleware/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-swagger-express-middleware/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Messinger",
        "url": "http://jamesmessinger.com"
    },
    "bugs": {
        "url": "https://github.com/BigstickCarpet/swagger-express-middleware/issues"
    },
    "dependencies": {
        "body-parser": "^1.13.1",
        "cookie-parser": "^1.3.5",
        "debug": "^2.2.0",
        "lodash": "^3.10.0",
        "mkdirp": "^0.5.1",
        "multer": "^0.1.8",
        "swagger-parser": "^2.5.0",
        "tv4": "^1.1.12",
        "type-is": "^1.6.4"
    },
    "description": "Swagger middleware and mocks for Express",
    "devDependencies": {
        "basic-auth": "^1.0.2",
        "chai": "^3.0.0",
        "chai-datetime": "^1.4.0",
        "coveralls": "^2.11.2",
        "express": "^4.13.0",
        "istanbul": "^0.3.17",
        "jscs": "^1.13.1",
        "jshint": "^2.8.0",
        "mocha": "^2.2.5",
        "npm-check-updates": "^1.5.1",
        "sinon": "^1.15.4",
        "supertest": "^1.0",
        "version-bump-prompt": "^1.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "dea8a8eeb22e5520c41175a5a075012abdf6952f",
        "tarball": "https://registry.npmjs.org/swagger-express-middleware/-/swagger-express-middleware-0.4.7.tgz"
    },
    "engines": {
        "node": ">=0.10.36",
        "npm": ">=2.0"
    },
    "gitHead": "b5a360289c7567052ca808df4fa4c73c427a8fd9",
    "homepage": "https://github.com/BigstickCarpet/swagger-express-middleware",
    "keywords": [
        "express",
        "swagger",
        "middleware",
        "mock",
        "fake",
        "stub",
        "rest",
        "api",
        "json"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "bigstickcarpet"
        }
    ],
    "name": "swagger-express-middleware",
    "optionalDependencies": {},
    "peerDependencies": {
        "express": "4.x"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/BigstickCarpet/swagger-express-middleware.git"
    },
    "scripts": {
        "build": "jshint . --verbose && jscs . --verbose",
        "mocha": "mocha --bail --recursive tests",
        "release": "npm run upgrade && npm run build && npm test && bump --prompt --tag --push --all && npm publish",
        "start": "cd samples && node sample2.js",
        "test": "istanbul cover _mocha -- --bail --recursive tests",
        "upgrade": "npm-check-updates -u && npm update"
    },
    "version": "0.4.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

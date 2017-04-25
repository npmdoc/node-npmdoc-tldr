# npmdoc-tldr

#### basic api documentation for  [tldr (v2.0.1)](http://tldr-pages.github.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-tldr.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-tldr) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-tldr.svg)](https://travis-ci.org/npmdoc/node-npmdoc-tldr)

#### Simplified and community-driven man pages

[![NPM](https://nodei.co/npm/tldr.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tldr)

- [https://npmdoc.github.io/node-npmdoc-tldr/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tldr/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tldr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tldr/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-tldr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-tldr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Romain Prieto"
    },
    "bin": {
        "tldr": "./bin/tldr"
    },
    "bugs": {
        "url": "https://github.com/tldr-pages/tldr-node-client/issues"
    },
    "dependencies": {
        "chalk": "~1.1.1",
        "commander": "~2.9.0",
        "fs-extra": "^0.30.0",
        "lodash.defaults": "~4.2.0",
        "lodash.get": "~4.4.2",
        "lodash.identity": "~3.0.0",
        "lodash.isempty": "~4.4.0",
        "lodash.sample": "~4.2.1",
        "lodash.unescape": "~4.0.0",
        "marked": "~0.3.6",
        "ms": "~0.7.1",
        "os-homedir": "~1.0.1",
        "request": "~2.75.0",
        "unzip2": "~0.2.5"
    },
    "description": "Simplified and community-driven man pages",
    "devDependencies": {
        "env-test": "*",
        "eslint": "*",
        "husky": "*",
        "mocha": "*",
        "should": "*",
        "sinon": "*"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "1240293c7e6962905d979d386cd604e046881e91",
        "tarball": "https://registry.npmjs.org/tldr/-/tldr-2.0.1.tgz"
    },
    "engines": {
        "node": ">=4.7"
    },
    "files": [
        "bin",
        "config.json",
        "lib",
        "LICENSE.md"
    ],
    "gitHead": "554ac6f768b06e07cc3fced23bb29b57774ef423",
    "homepage": "http://tldr-pages.github.io",
    "keywords": [
        "man",
        "unix",
        "linux",
        "osx",
        "commands",
        "command-line",
        "shell",
        "bash",
        "zsh"
    ],
    "license": "MIT",
    "main": "bin/tldr",
    "maintainers": [
        {
            "name": "agnivade"
        },
        {
            "name": "asyncadventures"
        },
        {
            "name": "igorshubovych"
        }
    ],
    "name": "tldr",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tldr-pages/tldr-node-client.git"
    },
    "scripts": {
        "example": "node ./bin/tldr tar",
        "lint": "eslint lib test bin/tldr",
        "precommit": "npm run lint && npm run test:quiet",
        "prepush": "npm run test:quiet",
        "start": "node ./bin/tldr",
        "test": "mocha test --require=env-test",
        "test:all": "npm run lint && npm test && npm run test:functional",
        "test:functional": "bash test/functional-test.sh",
        "test:quiet": "npm test --reporter=dot",
        "watch": "mocha test --require=env-test --reporter=min --watch --growl"
    },
    "version": "2.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

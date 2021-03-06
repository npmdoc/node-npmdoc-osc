# npmdoc-osc

#### api documentation for  [osc (v2.2.0)](https://github.com/colinbdclark/osc.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-osc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-osc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-osc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-osc)

#### A JavaScript Open Sound Control (OSC) library that works in Node.js and the browser.

[![NPM](https://nodei.co/npm/osc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/osc)

- [https://npmdoc.github.io/node-npmdoc-osc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-osc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-osc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-osc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-osc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-osc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Colin Clark"
    },
    "bugs": {
        "url": "https://github.com/colinbdclark/osc.js/issues"
    },
    "dependencies": {
        "long": "3.2.0",
        "serialport": "4.0.7",
        "slip": "1.0.2",
        "wolfy87-eventemitter": "5.0.0",
        "ws": "1.1.1"
    },
    "description": "A JavaScript Open Sound Control (OSC) library that works in Node.js and the browser.",
    "devDependencies": {
        "grunt": "~1.0.1",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-concat": "~1.0.1",
        "grunt-contrib-jshint": "~1.0.0",
        "grunt-contrib-uglify": "~1.0.1",
        "infusion": "2.0.0",
        "jquery": "3.1.1",
        "node-jqunit": "1.1.4",
        "requirejs": "2.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "c5db0a0e8823302da3d3207bae02c656cecf8b06",
        "tarball": "https://registry.npmjs.org/osc/-/osc-2.2.0.tgz"
    },
    "gitHead": "41e9969978c057c0b6675559fc2465ec53d49a4a",
    "homepage": "https://github.com/colinbdclark/osc.js",
    "keywords": [
        "Open Sound Control",
        "OSC",
        "sound",
        "audio",
        "music",
        "Web Socket",
        "UDP",
        "serial",
        "TCP"
    ],
    "license": "(MIT OR GPL-2.0)",
    "main": "src/platforms/osc-node.js",
    "maintainers": [
        {
            "name": "colinbdclark"
        }
    ],
    "name": "osc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/colinbdclark/osc.js.git"
    },
    "scripts": {
        "browser-test": "testem ci --file tests/testem.json",
        "clean-test": "./clean-npm.sh && npm install && npm test",
        "electron-test": "cd tests/electron-tests && npm install && node_modules/.bin/electron .",
        "test": "node tests/node-all-tests.js && grunt && npm run browser-test"
    },
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

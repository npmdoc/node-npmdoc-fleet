# npmdoc-fleet

#### api documentation for  fleet (v0.1.6)  [![npm package](https://img.shields.io/npm/v/npmdoc-fleet.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-fleet) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-fleet.svg)](https://travis-ci.org/npmdoc/node-npmdoc-fleet)

#### command a cluster of processes

[![NPM](https://nodei.co/npm/fleet.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fleet)

- [https://npmdoc.github.io/node-npmdoc-fleet/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fleet/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fleet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fleet/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-fleet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-fleet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "fleet",
    "description": "command a cluster of processes ",
    "version": "0.1.6",
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/fleet.git"
    },
    "main": "index.js",
    "bin": {
        "fleet": "bin/command.sh",
        "fleet-rootdir": "bin/rootdir.js",
        "fleet-help": "bin/help.sh",
        "fleet-remote": "bin/remote.js",
        "fleet-deploy": "bin/deploy.js",
        "fleet-drone": "bin/drone.js",
        "fleet-hub": "bin/hub.js",
        "fleet-ps": "bin/ps.js",
        "fleet-monitor": "bin/monitor.js",
        "fleet-spawn": "bin/spawn.js",
        "fleet-stop": "bin/stop.js",
        "fleet-exec": "bin/exec.js",
        "fleet-version": "bin/version.js"
    },
    "keywords": [
        "cluster",
        "management",
        "staging"
    ],
    "directories": {
        "doc": "doc",
        "example": "example",
        "test": "test",
        "man": "man1"
    },
    "scripts": {
        "test": "tap test/*.js"
    },
    "dependencies": {
        "propagit": "~0.6.4",
        "optimist": "~0.3.1",
        "mkdirp": "~0.3.0",
        "archy": "~0.0.2"
    },
    "devDependencies": {
        "tap": "~0.2.4",
        "seq": "~0.3.5",
        "ronn": "~0.3.8"
    },
    "engines": {
        "node": ">=0.6.0"
    },
    "license": "MIT",
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

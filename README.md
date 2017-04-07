# api documentation for  [guvnor (v3.5.17)](https://github.com/tableflip/guvnor)  [![npm package](https://img.shields.io/npm/v/npmdoc-guvnor.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-guvnor) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-guvnor.svg)](https://travis-ci.org/npmdoc/node-npmdoc-guvnor)
#### A node process manager that isn't spanners all the way down

[![NPM](https://nodei.co/npm/guvnor.png?downloads=true)](https://www.npmjs.com/package/guvnor)

[![apidoc](https://npmdoc.github.io/node-npmdoc-guvnor/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-guvnor_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-guvnor/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-guvnor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-guvnor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "bs": "bin/guv",
        "boss": "bin/guv",
        "bs-web": "bin/guv-web",
        "boss-web": "bin/guv-web",
        "guv": "bin/guv",
        "guv-web": "bin/guv-web",
        "guvnor": "bin/guv",
        "guvnor-web": "bin/guv-web"
    },
    "bugs": {
        "url": "https://github.com/tableflip/guvnor/issues"
    },
    "dependencies": {
        "ampersand-array-input-view": "^3.0",
        "ampersand-checkbox-view": "^2.0",
        "ampersand-collection": "^1.0",
        "ampersand-collection-view": "^1.0",
        "ampersand-dom": "^1.0",
        "ampersand-form-view": "^2.4.0",
        "ampersand-input-view": "^4.0.1",
        "ampersand-model": "^5.0.0",
        "ampersand-rest-collection": "^4.0.0",
        "ampersand-router": "^3.0.2",
        "ampersand-select-view": "^3.0.1",
        "ampersand-view": "^7.0",
        "ampersand-view-switcher": "^2.0",
        "andlog": "^1.0",
        "ansi-html": "^0.0",
        "async": "^0.9.2",
        "bcrypt": "^0.8",
        "bootstrap-notify": "^3.1.3",
        "boss-dnode": "^1.0",
        "clientconfig": "^1.0",
        "coercer": "^1.0",
        "coffee-script": "^1.9.0",
        "colors": "^1.0",
        "columbo": "^3.0",
        "commander": "^2.0",
        "component-emitter": "1.1.2",
        "copy-to": "^2.0",
        "cpu-stats": "^1.0",
        "domify": "^1.0",
        "domready": "^1.0",
        "duplex-maker": "^1.0.0",
        "etc-passwd": "^0.1",
        "event-loop-lag": "^1.0",
        "execSync": "^1.0",
        "extend": "^2.0",
        "favicon-setter": "^0.1",
        "freeport": "^1.0",
        "getconfig": "^2.1.0",
        "handlebars": "^3.0.0",
        "hapi": "^8.0",
        "hapi-auth-basic": "^2.0",
        "heapdump": "^0.3",
        "ini": "^1.3",
        "jquery": "^2.1.4",
        "jsonfile": "^2.0",
        "mdns": "^2.0",
        "meminfo": "^0.0",
        "mkdirp": "^0.5",
        "moment": "^2.0",
        "moonboots_hapi": "^4.0",
        "node-inspector": "^0.12.3",
        "output-buffer": "^1.0",
        "pem": "^1.0",
        "posix": "^4.0.0",
        "prettysize": "^0.0",
        "prompt": "^0.2",
        "rc": "github:achingbrain/rc#guvnor",
        "rimraf": "^2.0",
        "semver": "^4.3.3",
        "short-id": "^0.1.0",
        "shortid": "^2.1",
        "socket.io": "^1.2",
        "socket.io-client": "^1.2",
        "splitargs": "^0.0",
        "sprintf-js": "^1.0",
        "strip-ansi": "^2.0.1",
        "stylizer": "github:achingbrain/stylizer",
        "templatizer-hbs": "^0.0",
        "timeoutify": "^0.0",
        "underscore": "^1.0",
        "usage": "^0.7.0",
        "uuid": "^2.0",
        "wantsit": "^2.0",
        "wildemitter": "^1.0",
        "winston": "^1.0.0"
    },
    "description": "A node process manager that isn't spanners all the way down",
    "devDependencies": {
        "chai": "^2.0.0",
        "coveralls": "^2.8",
        "debug": "^2.1",
        "istanbul": "^0.3.0",
        "jsdom": "^4.0.4",
        "mocha": "^2.0",
        "mocha-jsdom": "^0.3.0",
        "pre-commit": "^1.0.4",
        "proxyquire": "^1.0",
        "sinon": "^1.8",
        "standard": "^3.2.0",
        "testsuite": "^1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "457ff10b0d848310928f9688f5c585aaf15c3ca6",
        "tarball": "https://registry.npmjs.org/guvnor/-/guvnor-3.5.17.tgz"
    },
    "gitHead": "31cb59cea212ad5ee162edc4d16071dca50dd994",
    "homepage": "https://github.com/tableflip/guvnor",
    "jshintConfig": {
        "asi": true,
        "browser": false,
        "browserify": true,
        "curly": false,
        "expr": true,
        "indent": 2,
        "loopfunc": true,
        "node": true,
        "trailing": true,
        "undef": true,
        "white": true,
        "mocha": true
    },
    "keywords": [
        "node",
        "process",
        "manager",
        "monitor",
        "runner",
        "auto restart",
        "cluster",
        "clustering",
        "pid",
        "user",
        "uid",
        "group",
        "gid",
        "uptime",
        "memory",
        "cpu",
        "boss",
        "process-boss"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "achingbrain",
            "email": "alex@achingbrain.net"
        }
    ],
    "name": "guvnor",
    "optionalDependencies": {
        "execSync": "^1.0",
        "mdns": "^2.0"
    },
    "pre-commit": [
        "lint",
        "test"
    ],
    "prefer-global": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/tableflip/guvnor.git"
    },
    "scripts": {
        "coveralls": "cat ./coverage/lcov.info | coveralls",
        "lint": "standard",
        "postinstall": "chmod +x scripts/init/sysv/guvnor",
        "test": "istanbul cover _mocha"
    },
    "standard": {
        "ignore": [
            "web/public/javascript/**",
            "web/client/templates.js",
            "test/**",
            "lib/web/index.js",
            "lib/common/HelpfulError.js",
            "web/client/views/host/resources.js"
        ]
    },
    "version": "3.5.17"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module guvnor](#apidoc.module.guvnor)
1.  [function <span class="apidocSignatureSpan">guvnor.</span>Remote ()](#apidoc.element.guvnor.Remote)
1.  object <span class="apidocSignatureSpan">guvnor.</span>Local

#### [module guvnor.Local](#apidoc.module.guvnor.Local)
1.  [function <span class="apidocSignatureSpan">guvnor.Local.</span>connect ()](#apidoc.element.guvnor.Local.connect)
1.  [function <span class="apidocSignatureSpan">guvnor.Local.</span>connectOrStart ()](#apidoc.element.guvnor.Local.connectOrStart)
1.  [function <span class="apidocSignatureSpan">guvnor.Local.</span>running ()](#apidoc.element.guvnor.Local.running)



# <a name="apidoc.module.guvnor"></a>[module guvnor](#apidoc.module.guvnor)

#### <a name="apidoc.element.guvnor.Remote"></a>[function <span class="apidocSignatureSpan">guvnor.</span>Remote ()](#apidoc.element.guvnor.Remote)
- description and source-code
```javascript
Remote = function () {
  var args = Array.prototype.slice.apply(arguments)

  createContainer(function (container) {
    var callback = args[args.length - 1]

    container._logger = findLogger.apply(null, args)

    container.register('logger', findLogger.apply(null, args))

    var remoteOptions = findRemoteOptions.apply(null, args)

    if (!remoteOptions) {
      return callback(new Error('Please pass an options object with your connection info'))
    }

    var host = remoteOptions.host
    var port = remoteOptions.port
    var secret = remoteOptions.secret
    var principal = remoteOptions.user || 'root'
    var timeout = remoteOptions.timeout || 10000
    var rpcTimeout = remoteOptions.rpcTimeout === undefined ? 30000 : remoteOptions.rpcTimeout

    container.create(require('./RemoteDaemon'), [host, port, principal, secret, timeout, rpcTimeout, callback], function (error,
remoteDaemon) {
      if (error) {
        callback(error)
      }

      remoteDaemon.connect(callback)
    })
  })
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.guvnor.Local"></a>[module guvnor.Local](#apidoc.module.guvnor.Local)

#### <a name="apidoc.element.guvnor.Local.connect"></a>[function <span class="apidocSignatureSpan">guvnor.Local.</span>connect ()](#apidoc.element.guvnor.Local.connect)
- description and source-code
```javascript
connect = function () {
  var args = Array.prototype.slice.call(arguments)

  createContainer(function (container) {
    findConfigAndLogger.call(null, container, args)

    container.find('localDaemon').connect(args[args.length - 1])
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.guvnor.Local.connectOrStart"></a>[function <span class="apidocSignatureSpan">guvnor.Local.</span>connectOrStart ()](#apidoc.element.guvnor.Local.connectOrStart)
- description and source-code
```javascript
connectOrStart = function () {
  var args = Array.prototype.slice.call(arguments)

  createContainer(function (container) {
    findConfigAndLogger.call(null, container, args)

    container.find('localDaemon').connectOrStart(args[args.length - 1])
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.guvnor.Local.running"></a>[function <span class="apidocSignatureSpan">guvnor.Local.</span>running ()](#apidoc.element.guvnor.Local.running)
- description and source-code
```javascript
running = function () {
  var args = Array.prototype.slice.call(arguments)

  createContainer(function (container) {
    findConfigAndLogger.call(null, container, args)

    var callback = args[args.length - 1]

    var connection = container.find('localDaemonUserConnection')
    connection.connect({}, function (error) {
      if (error && error.code === 'DAEMON_NOT_RUNNING') {
        return process.nextTick(callback.bind(callback, false))
      }

      process.nextTick(callback.bind(callback, true))

      connection.disconnect()
    })
  })
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

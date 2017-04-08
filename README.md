# api documentation for  [karma-coverage (v1.1.1)](https://github.com/karma-runner/karma-coverage#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-karma-coverage.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-karma-coverage) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-karma-coverage.svg)](https://travis-ci.org/npmdoc/node-npmdoc-karma-coverage)
#### A Karma plugin. Generate code coverage.

[![NPM](https://nodei.co/npm/karma-coverage.png?downloads=true)](https://www.npmjs.com/package/karma-coverage)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-coverage/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-karma-coverage%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-coverage/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-karma-coverage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-karma-coverage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "SATO taichi",
        "email": "ryushi@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/karma-runner/karma-coverage/issues"
    },
    "contributors": [
        {
            "name": "dignifiedquire",
            "email": "dignifiedquire@gmail.com"
        },
        {
            "name": "Friedel Ziegelmayer",
            "email": "dignifiedquire@gmail.com"
        },
        {
            "name": "Aymeric Beaumet",
            "email": "aymeric@beaumet.me"
        },
        {
            "name": "Tim Kang",
            "email": "timkang@ucla.edu"
        },
        {
            "name": "Nick Malaguti",
            "email": "nmalaguti@palantir.com"
        },
        {
            "name": "Maksim Ryzhikov",
            "email": "rv.maksim@gmail.com"
        },
        {
            "name": "Mark Ethan Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "nicojs",
            "email": "jansennico@gmail.com"
        },
        {
            "name": "Allen Bierbaum",
            "email": "abierbaum@gmail.com"
        },
        {
            "name": "Douglas Duteil",
            "email": "douglasduteil@gmail.com"
        },
        {
            "name": "Matt Winchester",
            "email": "m_winche@yahoo.com"
        },
        {
            "name": "Tanguy Krotoff",
            "email": "tkrotoff@gmail.com"
        },
        {
            "name": "Wei Kin Huang",
            "email": "weikin.huang04@gmail.com"
        },
        {
            "name": "Kyle Welsby",
            "email": "kyle@mekyle.com"
        },
        {
            "name": "Maciej Rzepiński",
            "email": "maciej.rzepinski@gmail.com"
        },
        {
            "name": "Joseph Connolly",
            "email": "joec@avinetworks.com"
        },
        {
            "name": "Marceli.no",
            "email": "me@marceli.no"
        },
        {
            "name": "James Talmage",
            "email": "james@talmage.io"
        },
        {
            "name": "Mark Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "Matt Lewis",
            "email": "matthew.lewis@socialsignin.co.uk"
        },
        {
            "name": "Chris Gladd",
            "email": "chris.m.gladd@gmail.com"
        },
        {
            "name": "Michael Stramel",
            "email": "m.stramel89@gmail.com"
        },
        {
            "name": "Greg Varsanyi",
            "email": "gvarsanyi@gmail.com"
        },
        {
            "name": "Nick Matantsev",
            "email": "nick.matantsev@gmail.com"
        },
        {
            "name": "Petar Manev",
            "email": "petar.manev2010@gmail.com"
        },
        {
            "name": "Robin Böhm",
            "email": "robinboehm@googlemail.com"
        },
        {
            "name": "Ron Derksen",
            "email": "ron.derksen@informaat.nl"
        },
        {
            "name": "Ruben Bridgewater",
            "email": "ruben.bridgewater@fintura.de"
        },
        {
            "name": "Sahat Yalkabov",
            "email": "sakhat@gmail.com"
        },
        {
            "name": "piecyk",
            "email": "piecyk@gmail.com"
        },
        {
            "name": "Tanjo, Hiroyuki",
            "email": "expheno@gmail.com"
        },
        {
            "name": "Taylor Hakes",
            "email": "taylor@taylorhakes.com"
        },
        {
            "name": "Dmitry Petrov",
            "email": "dpetroff@gmail.com"
        },
        {
            "name": "Timo Tijhof",
            "email": "krinklemail@gmail.com"
        },
        {
            "name": "Tom Kirkpatrick",
            "email": "tom@systemseed.com"
        },
        {
            "name": "Tyler Waters",
            "email": "tyler.waters@gmail.com"
        },
        {
            "name": "Vincent Lemeunier",
            "email": "vincent.lemeunier+git@gmail.com"
        },
        {
            "name": "Dan Watling",
            "email": "dan@synaptik.com"
        },
        {
            "name": "terussell85",
            "email": "terussell85@gmail.com"
        },
        {
            "name": "Yusuke Suzuki",
            "email": "utatane.tea@gmail.com"
        },
        {
            "name": "aprooks",
            "email": "alexander.prooks@gmail.com"
        },
        {
            "name": "carlos",
            "email": "cafesanu@gmail.com"
        },
        {
            "name": "Clayton Watts",
            "email": "cletusw@gmail.com"
        },
        {
            "name": "fbergr",
            "email": "fbergr@gmail.com"
        },
        {
            "name": "Joshua Appelman",
            "email": "jappelman@xebia.com"
        },
        {
            "name": "Julie",
            "email": "ju.ralph@gmail.com"
        },
        {
            "name": "Lloyd Smith II",
            "email": "lloyd@trove.com"
        }
    ],
    "dependencies": {
        "dateformat": "^1.0.6",
        "istanbul": "^0.4.0",
        "lodash": "^3.8.0",
        "minimatch": "^3.0.0",
        "source-map": "^0.5.1"
    },
    "description": "A Karma plugin. Generate code coverage.",
    "devDependencies": {
        "chai": "^3.3.0",
        "eslint": "^2.2.0",
        "eslint-config-standard": "^5.1.0",
        "eslint-plugin-promise": "^1.1.0",
        "eslint-plugin-react": "^4.1.0",
        "eslint-plugin-standard": "^1.1.0",
        "grunt": "^0.4.1",
        "grunt-bump": "^0.7.0",
        "grunt-conventional-changelog": "^6.1.0",
        "grunt-conventional-github-releaser": "^1.0.0",
        "grunt-eslint": "^18.0.0",
        "grunt-karma": "1.x || ^0.12.0",
        "grunt-npm": "^0.0.2",
        "grunt-simple-mocha": "^0.4.0",
        "ibrik": "^2.0.0",
        "karma": "1.x || ^0.13.7",
        "karma-coffee-preprocessor": "1.x || ^0.3.0",
        "karma-firefox-launcher": "1.x || ^0.1.6",
        "karma-mocha": "1.x || ^0.2.0",
        "karma-requirejs": "1.x || ^0.2.2",
        "load-grunt-tasks": "^3.2.0",
        "mocha": "^2.2.5",
        "mocks": "0.0.15",
        "requirejs": "^2.1.20",
        "sinon": "^1.14.1",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5aff8b39cf6994dc22de4c84362c76001b637cf6",
        "tarball": "https://registry.npmjs.org/karma-coverage/-/karma-coverage-1.1.1.tgz"
    },
    "gitHead": "8b6ee3b006a20884309a15f6112952b633d07dbd",
    "homepage": "https://github.com/karma-runner/karma-coverage#readme",
    "keywords": [
        "karma-plugin",
        "karma-preprocessor",
        "karma-reporter",
        "coverage",
        "istanbul"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "vojtajina",
            "email": "vojta.jina+npm@gmail.com"
        },
        {
            "name": "zzo",
            "email": "mark@zzo.com"
        },
        {
            "name": "dignifiedquire",
            "email": "dignifiedquire@gmail.com"
        }
    ],
    "name": "karma-coverage",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/karma-runner/karma-coverage.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "1.1.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module karma-coverage](#apidoc.module.karma-coverage)
1.  [function <span class="apidocSignatureSpan">karma-coverage.</span>in_memory_report (opt)](#apidoc.element.karma-coverage.in_memory_report)
1.  [function <span class="apidocSignatureSpan">karma-coverage.</span>source_cache_store (opts)](#apidoc.element.karma-coverage.source_cache_store)
1.  object <span class="apidocSignatureSpan">karma-coverage.</span>coverage_map
1.  object <span class="apidocSignatureSpan">karma-coverage.</span>in_memory_report.prototype
1.  object <span class="apidocSignatureSpan">karma-coverage.</span>source_cache
1.  object <span class="apidocSignatureSpan">karma-coverage.</span>source_cache_store.prototype

#### [module karma-coverage.coverage_map](#apidoc.module.karma-coverage.coverage_map)
1.  [function <span class="apidocSignatureSpan">karma-coverage.coverage_map.</span>add (coverageObj)](#apidoc.element.karma-coverage.coverage_map.add)
1.  [function <span class="apidocSignatureSpan">karma-coverage.coverage_map.</span>get ()](#apidoc.element.karma-coverage.coverage_map.get)
1.  [function <span class="apidocSignatureSpan">karma-coverage.coverage_map.</span>reset ()](#apidoc.element.karma-coverage.coverage_map.reset)

#### [module karma-coverage.in_memory_report](#apidoc.module.karma-coverage.in_memory_report)
1.  [function <span class="apidocSignatureSpan">karma-coverage.</span>in_memory_report (opt)](#apidoc.element.karma-coverage.in_memory_report.in_memory_report)
1.  [function <span class="apidocSignatureSpan">karma-coverage.in_memory_report.</span>super_ ()](#apidoc.element.karma-coverage.in_memory_report.super_)
1.  string <span class="apidocSignatureSpan">karma-coverage.in_memory_report.</span>TYPE

#### [module karma-coverage.in_memory_report.prototype](#apidoc.module.karma-coverage.in_memory_report.prototype)
1.  [function <span class="apidocSignatureSpan">karma-coverage.in_memory_report.prototype.</span>writeReport (collector, sync)](#apidoc.element.karma-coverage.in_memory_report.prototype.writeReport)

#### [module karma-coverage.source_cache](#apidoc.module.karma-coverage.source_cache)
1.  [function <span class="apidocSignatureSpan">karma-coverage.source_cache.</span>get (basePath)](#apidoc.element.karma-coverage.source_cache.get)

#### [module karma-coverage.source_cache_store](#apidoc.module.karma-coverage.source_cache_store)
1.  [function <span class="apidocSignatureSpan">karma-coverage.</span>source_cache_store (opts)](#apidoc.element.karma-coverage.source_cache_store.source_cache_store)
1.  [function <span class="apidocSignatureSpan">karma-coverage.source_cache_store.</span>super_ ()](#apidoc.element.karma-coverage.source_cache_store.super_)
1.  string <span class="apidocSignatureSpan">karma-coverage.source_cache_store.</span>TYPE

#### [module karma-coverage.source_cache_store.prototype](#apidoc.module.karma-coverage.source_cache_store.prototype)
1.  [function <span class="apidocSignatureSpan">karma-coverage.source_cache_store.prototype.</span>get (key)](#apidoc.element.karma-coverage.source_cache_store.prototype.get)
1.  [function <span class="apidocSignatureSpan">karma-coverage.source_cache_store.prototype.</span>hasKey (key)](#apidoc.element.karma-coverage.source_cache_store.prototype.hasKey)
1.  [function <span class="apidocSignatureSpan">karma-coverage.source_cache_store.prototype.</span>keys ()](#apidoc.element.karma-coverage.source_cache_store.prototype.keys)
1.  [function <span class="apidocSignatureSpan">karma-coverage.source_cache_store.prototype.</span>set (key, contents)](#apidoc.element.karma-coverage.source_cache_store.prototype.set)



# <a name="apidoc.module.karma-coverage"></a>[module karma-coverage](#apidoc.module.karma-coverage)

#### <a name="apidoc.element.karma-coverage.in_memory_report"></a>[function <span class="apidocSignatureSpan">karma-coverage.</span>in_memory_report (opt)](#apidoc.element.karma-coverage.in_memory_report)
- description and source-code
```javascript
function InMemoryReport(opt) {
  this.opt = opt
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma-coverage.source_cache_store"></a>[function <span class="apidocSignatureSpan">karma-coverage.</span>source_cache_store (opts)](#apidoc.element.karma-coverage.source_cache_store)
- description and source-code
```javascript
source_cache_store = function (opts) {
  Store.call(this, opts)
  opts = opts || {}
  this.sourceCache = opts.sourceCache
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma-coverage.coverage_map"></a>[module karma-coverage.coverage_map](#apidoc.module.karma-coverage.coverage_map)

#### <a name="apidoc.element.karma-coverage.coverage_map.add"></a>[function <span class="apidocSignatureSpan">karma-coverage.coverage_map.</span>add (coverageObj)](#apidoc.element.karma-coverage.coverage_map.add)
- description and source-code
```javascript
function add(coverageObj) {
  coverageMap[coverageObj.path] = coverageObj
}
```
- example usage
```shell
...
  coverageObjRegex.lastIndex = 0

  var coverageObjMatch = coverageObjRegex.exec(instrumentedCode)

  if (coverageObjMatch !== null) {
    var coverageObj = JSON.parse(coverageObjMatch[0])

    coverageMap.add(coverageObj)
  }
}

// RequireJS expects JavaScript files to end with '.js'
if (useJSExtensionForCoffeeScript && instrumenterLiteral === 'ibrik') {
  file.path = file.path.replace(/\.coffee$/, '.js')
}
...
```

#### <a name="apidoc.element.karma-coverage.coverage_map.get"></a>[function <span class="apidocSignatureSpan">karma-coverage.coverage_map.</span>get ()](#apidoc.element.karma-coverage.coverage_map.get)
- description and source-code
```javascript
function get() {
  return coverageMap
}
```
- example usage
```shell
...
  if (coverageReporter) {
instrumenterOverrides = coverageReporter.instrumenter
instrumenters = extend({istanbul: istanbul}, coverageReporter.instrumenters)
includeAllSources = coverageReporter.includeAllSources === true
useJSExtensionForCoffeeScript = coverageReporter.useJSExtensionForCoffeeScript === true
  }

  var sourceCache = globalSourceCache.get(basePath)

  var instrumentersOptions = _.reduce(instrumenters, function getInstumenterOptions (memo, instrument, name) {
memo[name] = {}

if (coverageReporter && coverageReporter.instrumenterOptions) {
  memo[name] = coverageReporter.instrumenterOptions[name]
}
...
```

#### <a name="apidoc.element.karma-coverage.coverage_map.reset"></a>[function <span class="apidocSignatureSpan">karma-coverage.coverage_map.</span>reset ()](#apidoc.element.karma-coverage.coverage_map.reset)
- description and source-code
```javascript
function reset() {
  coverageMap = {}
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma-coverage.in_memory_report"></a>[module karma-coverage.in_memory_report](#apidoc.module.karma-coverage.in_memory_report)

#### <a name="apidoc.element.karma-coverage.in_memory_report.in_memory_report"></a>[function <span class="apidocSignatureSpan">karma-coverage.</span>in_memory_report (opt)](#apidoc.element.karma-coverage.in_memory_report.in_memory_report)
- description and source-code
```javascript
function InMemoryReport(opt) {
  this.opt = opt
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma-coverage.in_memory_report.super_"></a>[function <span class="apidocSignatureSpan">karma-coverage.in_memory_report.</span>super_ ()](#apidoc.element.karma-coverage.in_memory_report.super_)
- description and source-code
```javascript
function Report() {
    EventEmitter.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma-coverage.in_memory_report.prototype"></a>[module karma-coverage.in_memory_report.prototype](#apidoc.module.karma-coverage.in_memory_report.prototype)

#### <a name="apidoc.element.karma-coverage.in_memory_report.prototype.writeReport"></a>[function <span class="apidocSignatureSpan">karma-coverage.in_memory_report.prototype.</span>writeReport (collector, sync)](#apidoc.element.karma-coverage.in_memory_report.prototype.writeReport)
- description and source-code
```javascript
writeReport = function (collector, sync) {
  if (!this.opt.emitter || !this.opt.emitter.emit) {
    console.error('Could not raise "coverage_complete" event, missing emitter because it was not supplied during initialization
of the reporter')
  } else {
    this.opt.emitter.emit('coverage_complete', this.opt.browser, collector.getFinalCoverage())
  }
}
```
- example usage
```shell
...
  try {
    if (typeof config._onWriteReport === 'function') {
      var newCollector = config._onWriteReport(collector)
      if (typeof newCollector === 'object') {
        collector = newCollector
      }
    }
    reporter.writeReport(collector, true)
  } catch (e) {
    log.error(e)
  }

  --pendingFileWritings
}
...
```



# <a name="apidoc.module.karma-coverage.source_cache"></a>[module karma-coverage.source_cache](#apidoc.module.karma-coverage.source_cache)

#### <a name="apidoc.element.karma-coverage.source_cache.get"></a>[function <span class="apidocSignatureSpan">karma-coverage.source_cache.</span>get (basePath)](#apidoc.element.karma-coverage.source_cache.get)
- description and source-code
```javascript
function get(basePath) {
  if (!cache[basePath]) {
    cache[basePath] = {}
  }

  return cache[basePath]
}
```
- example usage
```shell
...
  if (coverageReporter) {
instrumenterOverrides = coverageReporter.instrumenter
instrumenters = extend({istanbul: istanbul}, coverageReporter.instrumenters)
includeAllSources = coverageReporter.includeAllSources === true
useJSExtensionForCoffeeScript = coverageReporter.useJSExtensionForCoffeeScript === true
  }

  var sourceCache = globalSourceCache.get(basePath)

  var instrumentersOptions = _.reduce(instrumenters, function getInstumenterOptions (memo, instrument, name) {
memo[name] = {}

if (coverageReporter && coverageReporter.instrumenterOptions) {
  memo[name] = coverageReporter.instrumenterOptions[name]
}
...
```



# <a name="apidoc.module.karma-coverage.source_cache_store"></a>[module karma-coverage.source_cache_store](#apidoc.module.karma-coverage.source_cache_store)

#### <a name="apidoc.element.karma-coverage.source_cache_store.source_cache_store"></a>[function <span class="apidocSignatureSpan">karma-coverage.</span>source_cache_store (opts)](#apidoc.element.karma-coverage.source_cache_store.source_cache_store)
- description and source-code
```javascript
source_cache_store = function (opts) {
  Store.call(this, opts)
  opts = opts || {}
  this.sourceCache = opts.sourceCache
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma-coverage.source_cache_store.super_"></a>[function <span class="apidocSignatureSpan">karma-coverage.source_cache_store.</span>super_ ()](#apidoc.element.karma-coverage.source_cache_store.super_)
- description and source-code
```javascript
function Store() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma-coverage.source_cache_store.prototype"></a>[module karma-coverage.source_cache_store.prototype](#apidoc.module.karma-coverage.source_cache_store.prototype)

#### <a name="apidoc.element.karma-coverage.source_cache_store.prototype.get"></a>[function <span class="apidocSignatureSpan">karma-coverage.source_cache_store.prototype.</span>get (key)](#apidoc.element.karma-coverage.source_cache_store.prototype.get)
- description and source-code
```javascript
get = function (key) {
  return this.sourceCache[key]
}
```
- example usage
```shell
...
  if (coverageReporter) {
instrumenterOverrides = coverageReporter.instrumenter
instrumenters = extend({istanbul: istanbul}, coverageReporter.instrumenters)
includeAllSources = coverageReporter.includeAllSources === true
useJSExtensionForCoffeeScript = coverageReporter.useJSExtensionForCoffeeScript === true
  }

  var sourceCache = globalSourceCache.get(basePath)

  var instrumentersOptions = _.reduce(instrumenters, function getInstumenterOptions (memo, instrument, name) {
memo[name] = {}

if (coverageReporter && coverageReporter.instrumenterOptions) {
  memo[name] = coverageReporter.instrumenterOptions[name]
}
...
```

#### <a name="apidoc.element.karma-coverage.source_cache_store.prototype.hasKey"></a>[function <span class="apidocSignatureSpan">karma-coverage.source_cache_store.prototype.</span>hasKey (key)](#apidoc.element.karma-coverage.source_cache_store.prototype.hasKey)
- description and source-code
```javascript
hasKey = function (key) {
  return this.sourceCache.hasOwnProperty(key)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma-coverage.source_cache_store.prototype.keys"></a>[function <span class="apidocSignatureSpan">karma-coverage.source_cache_store.prototype.</span>keys ()](#apidoc.element.karma-coverage.source_cache_store.prototype.keys)
- description and source-code
```javascript
keys = function () {
  throw new Error('Not implemented')
}
```
- example usage
```shell
...
    done(content)
  }
}

// check instrumenter override requests
function checkInstrumenters () {
  return _.reduce(instrumenterOverrides, function (acc, literal, pattern) {
    if (!_.includes(_.keys(instrumenters), String(literal))) {
      log.error('Unknown instrumenter: %s', literal)
      return false
    }
    return acc
  }, true)
}
...
```

#### <a name="apidoc.element.karma-coverage.source_cache_store.prototype.set"></a>[function <span class="apidocSignatureSpan">karma-coverage.source_cache_store.prototype.</span>set (key, contents)](#apidoc.element.karma-coverage.source_cache_store.prototype.set)
- description and source-code
```javascript
set = function (key, contents) {
  throw new Error('Not applicable')
}
```
- example usage
```shell
...
## Examples

### Basic

'''javascript
// karma.conf.js
module.exports = function(config) {
  config.set({
files: [
  'src/**/*.js',
  'test/**/*.js'
],

// coverage reporter generates the coverage
reporters: ['progress', 'coverage'],
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

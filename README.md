# api documentation for  [csv (v1.1.1)](http://www.adaltas.com/projects/node-csv/)  [![npm package](https://img.shields.io/npm/v/npmdoc-csv.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-csv) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-csv.svg)](https://travis-ci.org/npmdoc/node-npmdoc-csv)
#### CSV parser with simple api, full of options and tested against large datasets.

[![NPM](https://nodei.co/npm/csv.png?downloads=true)](https://www.npmjs.com/package/csv)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csv/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-csv_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csv/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-csv/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-csv/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Worms",
        "email": "david@adaltas.com",
        "url": "http://www.adaltas.com"
    },
    "bugs": {
        "url": "https://github.com/wdavidw/node-csv/issues"
    },
    "contributors": [
        {
            "name": "David Worms",
            "email": "david@adaltas.com",
            "url": "http://www.adaltas.com"
        }
    ],
    "dependencies": {
        "csv-generate": "^1.0.0",
        "csv-parse": "^1.2.0",
        "csv-stringify": "^1.0.0",
        "stream-transform": "^0.1.0"
    },
    "description": "CSV parser with simple api, full of options and tested against large datasets.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "d9952d59b1f964a7afbcdd804d6818a73199a477",
        "tarball": "https://registry.npmjs.org/csv/-/csv-1.1.1.tgz"
    },
    "engines": {
        "node": ">= 0.1.90"
    },
    "gitHead": "f3520ddeaf087ffb436b3909e447ef3e5fcef316",
    "homepage": "http://www.adaltas.com/projects/node-csv/",
    "keywords": [
        "node",
        "csv",
        "tsv",
        "parser",
        "parse",
        "stringifier",
        "stringify"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib",
    "maintainers": [
        {
            "name": "david",
            "email": "david@adaltas.com"
        }
    ],
    "name": "csv",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wdavidw/node-csv.git"
    },
    "scripts": {},
    "version": "1.1.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module csv](#apidoc.module.csv)
1.  [function <span class="apidocSignatureSpan">csv.</span>generate ()](#apidoc.element.csv.generate)
1.  [function <span class="apidocSignatureSpan">csv.</span>generate.Generator (options1)](#apidoc.element.csv.generate.Generator)
1.  [function <span class="apidocSignatureSpan">csv.</span>parse ()](#apidoc.element.csv.parse)
1.  [function <span class="apidocSignatureSpan">csv.</span>parse.Parser (options)](#apidoc.element.csv.parse.Parser)
1.  [function <span class="apidocSignatureSpan">csv.</span>stringify ()](#apidoc.element.csv.stringify)
1.  [function <span class="apidocSignatureSpan">csv.</span>stringify.Stringifier (opts)](#apidoc.element.csv.stringify.Stringifier)
1.  [function <span class="apidocSignatureSpan">csv.</span>transform ()](#apidoc.element.csv.transform)
1.  [function <span class="apidocSignatureSpan">csv.</span>transform.Transformer (options1, transform1)](#apidoc.element.csv.transform.Transformer)
1.  object <span class="apidocSignatureSpan">csv.</span>generate.Generator.prototype
1.  object <span class="apidocSignatureSpan">csv.</span>parse.Parser.prototype
1.  object <span class="apidocSignatureSpan">csv.</span>stringify.Stringifier.prototype
1.  object <span class="apidocSignatureSpan">csv.</span>transform.Transformer.prototype

#### [module csv.generate](#apidoc.module.csv.generate)
1.  [function <span class="apidocSignatureSpan">csv.</span>generate ()](#apidoc.element.csv.generate.generate)
1.  [function <span class="apidocSignatureSpan">csv.generate.</span>Generator (options1)](#apidoc.element.csv.generate.Generator)

#### [module csv.generate.Generator](#apidoc.module.csv.generate.Generator)
1.  [function <span class="apidocSignatureSpan">csv.generate.</span>Generator (options1)](#apidoc.element.csv.generate.Generator.Generator)
1.  [function <span class="apidocSignatureSpan">csv.generate.Generator.</span>ascii (gen)](#apidoc.element.csv.generate.Generator.ascii)
1.  [function <span class="apidocSignatureSpan">csv.generate.Generator.</span>bool (gen)](#apidoc.element.csv.generate.Generator.bool)
1.  [function <span class="apidocSignatureSpan">csv.generate.Generator.</span>int (gen)](#apidoc.element.csv.generate.Generator.int)
1.  [function <span class="apidocSignatureSpan">csv.generate.Generator.</span>super_ (options)](#apidoc.element.csv.generate.Generator.super_)

#### [module csv.generate.Generator.prototype](#apidoc.module.csv.generate.Generator.prototype)
1.  [function <span class="apidocSignatureSpan">csv.generate.Generator.prototype.</span>_read (size)](#apidoc.element.csv.generate.Generator.prototype._read)
1.  [function <span class="apidocSignatureSpan">csv.generate.Generator.prototype.</span>end ()](#apidoc.element.csv.generate.Generator.prototype.end)
1.  [function <span class="apidocSignatureSpan">csv.generate.Generator.prototype.</span>random ()](#apidoc.element.csv.generate.Generator.prototype.random)

#### [module csv.parse](#apidoc.module.csv.parse)
1.  [function <span class="apidocSignatureSpan">csv.</span>parse ()](#apidoc.element.csv.parse.parse)
1.  [function <span class="apidocSignatureSpan">csv.parse.</span>Parser (options)](#apidoc.element.csv.parse.Parser)

#### [module csv.parse.Parser](#apidoc.module.csv.parse.Parser)
1.  [function <span class="apidocSignatureSpan">csv.parse.</span>Parser (options)](#apidoc.element.csv.parse.Parser.Parser)
1.  [function <span class="apidocSignatureSpan">csv.parse.Parser.</span>super_ (options)](#apidoc.element.csv.parse.Parser.super_)

#### [module csv.parse.Parser.prototype](#apidoc.module.csv.parse.Parser.prototype)
1.  [function <span class="apidocSignatureSpan">csv.parse.Parser.prototype.</span>__push (line)](#apidoc.element.csv.parse.Parser.prototype.__push)
1.  [function <span class="apidocSignatureSpan">csv.parse.Parser.prototype.</span>__write (chars, end)](#apidoc.element.csv.parse.Parser.prototype.__write)
1.  [function <span class="apidocSignatureSpan">csv.parse.Parser.prototype.</span>_flush (callback)](#apidoc.element.csv.parse.Parser.prototype._flush)
1.  [function <span class="apidocSignatureSpan">csv.parse.Parser.prototype.</span>_transform (chunk, encoding, callback)](#apidoc.element.csv.parse.Parser.prototype._transform)

#### [module csv.stringify](#apidoc.module.csv.stringify)
1.  [function <span class="apidocSignatureSpan">csv.</span>stringify ()](#apidoc.element.csv.stringify.stringify)
1.  [function <span class="apidocSignatureSpan">csv.stringify.</span>Stringifier (opts)](#apidoc.element.csv.stringify.Stringifier)

#### [module csv.stringify.Stringifier](#apidoc.module.csv.stringify.Stringifier)
1.  [function <span class="apidocSignatureSpan">csv.stringify.</span>Stringifier (opts)](#apidoc.element.csv.stringify.Stringifier.Stringifier)
1.  [function <span class="apidocSignatureSpan">csv.stringify.Stringifier.</span>super_ (options)](#apidoc.element.csv.stringify.Stringifier.super_)

#### [module csv.stringify.Stringifier.prototype](#apidoc.module.csv.stringify.Stringifier.prototype)
1.  [function <span class="apidocSignatureSpan">csv.stringify.Stringifier.prototype.</span>_transform (chunk, encoding, callback)](#apidoc.element.csv.stringify.Stringifier.prototype._transform)
1.  [function <span class="apidocSignatureSpan">csv.stringify.Stringifier.prototype.</span>end (chunk, encoding, callback)](#apidoc.element.csv.stringify.Stringifier.prototype.end)
1.  [function <span class="apidocSignatureSpan">csv.stringify.Stringifier.prototype.</span>headers ()](#apidoc.element.csv.stringify.Stringifier.prototype.headers)
1.  [function <span class="apidocSignatureSpan">csv.stringify.Stringifier.prototype.</span>stringify (line)](#apidoc.element.csv.stringify.Stringifier.prototype.stringify)
1.  [function <span class="apidocSignatureSpan">csv.stringify.Stringifier.prototype.</span>write (chunk, encoding, callback)](#apidoc.element.csv.stringify.Stringifier.prototype.write)

#### [module csv.transform](#apidoc.module.csv.transform)
1.  [function <span class="apidocSignatureSpan">csv.</span>transform ()](#apidoc.element.csv.transform.transform)
1.  [function <span class="apidocSignatureSpan">csv.transform.</span>Transformer (options1, transform1)](#apidoc.element.csv.transform.Transformer)

#### [module csv.transform.Transformer](#apidoc.module.csv.transform.Transformer)
1.  [function <span class="apidocSignatureSpan">csv.transform.</span>Transformer (options1, transform1)](#apidoc.element.csv.transform.Transformer.Transformer)
1.  [function <span class="apidocSignatureSpan">csv.transform.Transformer.</span>super_ (options)](#apidoc.element.csv.transform.Transformer.super_)

#### [module csv.transform.Transformer.prototype](#apidoc.module.csv.transform.Transformer.prototype)
1.  [function <span class="apidocSignatureSpan">csv.transform.Transformer.prototype.</span>_done (err, chunks, cb)](#apidoc.element.csv.transform.Transformer.prototype._done)
1.  [function <span class="apidocSignatureSpan">csv.transform.Transformer.prototype.</span>_flush (cb)](#apidoc.element.csv.transform.Transformer.prototype._flush)
1.  [function <span class="apidocSignatureSpan">csv.transform.Transformer.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.csv.transform.Transformer.prototype._transform)



# <a name="apidoc.module.csv"></a>[module csv](#apidoc.module.csv)

#### <a name="apidoc.element.csv.generate"></a>[function <span class="apidocSignatureSpan">csv.</span>generate ()](#apidoc.element.csv.generate)
- description and source-code
```javascript
generate = function () {
  var callback, data, generator, options;
  if (arguments.length === 2) {
    options = arguments[0];
    callback = arguments[1];
  } else if (arguments.length === 1) {
    if (typeof arguments[0] === 'function') {
      options = {};
      callback = arguments[0];
    } else {
      options = arguments[0];
    }
  } else if (arguments.length === 0) {
    options = {};
  }
  generator = new Generator(options);
  if (callback) {
    data = [];
    generator.on('readable', function() {
      var d, results;
      results = [];
      while (d = generator.read()) {
        results.push(data.push(options.objectMode ? d : d.toString()));
      }
      return results;
    });
    generator.on('error', callback);
    generator.on('end', function() {
      return callback(null, options.objectMode ? data : data.join(''));
    });
  }
  return generator;
}
```
- example usage
```shell
...
### Callback example

Execute this script with the command 'node samples/callback.js'.

'''javascript
var csv = require('csv');

csv.generate({seed: 1, columns: 2, length: 20}, function(err, data){
csv.parse(data, function(err, data){
  csv.transform(data, function(data){
    return data.map(function(value){return value.toUpperCase()});
  }, function(err, data){
    csv.stringify(data, function(err, data){
      process.stdout.write(data);
    });
...
```

#### <a name="apidoc.element.csv.generate.Generator"></a>[function <span class="apidocSignatureSpan">csv.</span>generate.Generator (options1)](#apidoc.element.csv.generate.Generator)
- description and source-code
```javascript
generate.Generator = function (options1) {
  var base, base1, base2, base3, base4, base5, base6, base7, base8, i, j, len, ref, v;
  this.options = options1 != null ? options1 : {};
  stream.Readable.call(this, this.options);
  this.options.count = 0;
  if ((base = this.options).duration == null) {
    base.duration = 4 * 60 * 1000;
  }
  if ((base1 = this.options).columns == null) {
    base1.columns = 8;
  }
  if ((base2 = this.options).max_word_length == null) {
    base2.max_word_length = 16;
  }
  if ((base3 = this.options).fixed_size == null) {
    base3.fixed_size = false;
  }
  if (this.fixed_size_buffer == null) {
    this.fixed_size_buffer = '';
  }
  if ((base4 = this.options).start == null) {
    base4.start = Date.now();
  }
  if ((base5 = this.options).end == null) {
    base5.end = null;
  }
  if ((base6 = this.options).seed == null) {
    base6.seed = false;
  }
  if ((base7 = this.options).length == null) {
    base7.length = -1;
  }
  if ((base8 = this.options).delimiter == null) {
    base8.delimiter = ',';
  }
  this.count_written = 0;
  this.count_created = 0;
  if (typeof this.options.columns === 'number') {
    this.options.columns = new Array(this.options.columns);
  }
  ref = this.options.columns;
  for (i = j = 0, len = ref.length; j < len; i = ++j) {
    v = ref[i];
    if (v == null) {
      v = 'ascii';
    }
    if (typeof v === 'string') {
      this.options.columns[i] = Generator[v];
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.parse"></a>[function <span class="apidocSignatureSpan">csv.</span>parse ()](#apidoc.element.csv.parse)
- description and source-code
```javascript
parse = function () {
  var callback, called, chunks, data, options, parser;
  if (arguments.length === 3) {
    data = arguments[0];
    options = arguments[1];
    callback = arguments[2];
    if (typeof callback !== 'function') {
      throw Error("Invalid callback argument: " + (JSON.stringify(callback)));
    }
    if (!(typeof data === 'string' || Buffer.isBuffer(arguments[0]))) {
      return callback(Error("Invalid data argument: " + (JSON.stringify(data))));
    }
  } else if (arguments.length === 2) {
    if (typeof arguments[0] === 'string' || Buffer.isBuffer(arguments[0])) {
      data = arguments[0];
    } else {
      options = arguments[0];
    }
    if (typeof arguments[1] === 'function') {
      callback = arguments[1];
    } else {
      options = arguments[1];
    }
  } else if (arguments.length === 1) {
    if (typeof arguments[0] === 'function') {
      callback = arguments[0];
    } else {
      options = arguments[0];
    }
  }
  if (options == null) {
    options = {};
  }
  parser = new Parser(options);
  if (data != null) {
    process.nextTick(function() {
      parser.write(data);
      return parser.end();
    });
  }
  if (callback) {
    called = false;
    chunks = options.objname ? {} : [];
    parser.on('readable', function() {
      var chunk, results;
      results = [];
      while (chunk = parser.read()) {
        if (options.objname) {
          results.push(chunks[chunk[0]] = chunk[1]);
        } else {
          results.push(chunks.push(chunk));
        }
      }
      return results;
    });
    parser.on('error', function(err) {
      called = true;
      return callback(err);
    });
    parser.on('end', function() {
      if (!called) {
        return callback(null, chunks);
      }
    });
  }
  return parser;
}
```
- example usage
```shell
...

Execute this script with the command 'node samples/callback.js'.

'''javascript
var csv = require('csv');

csv.generate({seed: 1, columns: 2, length: 20}, function(err, data){
csv.parse(data, function(err, data){
  csv.transform(data, function(data){
    return data.map(function(value){return value.toUpperCase()});
  }, function(err, data){
    csv.stringify(data, function(err, data){
      process.stdout.write(data);
    });
  });
...
```

#### <a name="apidoc.element.csv.parse.Parser"></a>[function <span class="apidocSignatureSpan">csv.</span>parse.Parser (options)](#apidoc.element.csv.parse.Parser)
- description and source-code
```javascript
parse.Parser = function (options) {
  var base, base1, base10, base11, base12, base13, base14, base15, base16, base2, base3, base4, base5, base6, base7, base8, base9
, k, v;
  if (options == null) {
    options = {};
  }
  options.objectMode = true;
  this.options = {};
  for (k in options) {
    v = options[k];
    this.options[k] = v;
  }
  stream.Transform.call(this, this.options);
  if ((base = this.options).rowDelimiter == null) {
    base.rowDelimiter = null;
  }
  if (typeof this.options.rowDelimiter === 'string') {
    this.options.rowDelimiter = [this.options.rowDelimiter];
  }
  if ((base1 = this.options).delimiter == null) {
    base1.delimiter = ',';
  }
  if ((base2 = this.options).quote == null) {
    base2.quote = '"';
  }
  if ((base3 = this.options).escape == null) {
    base3.escape = '"';
  }
  if ((base4 = this.options).columns == null) {
    base4.columns = null;
  }
  if ((base5 = this.options).comment == null) {
    base5.comment = '';
  }
  if ((base6 = this.options).objname == null) {
    base6.objname = false;
  }
  if ((base7 = this.options).trim == null) {
    base7.trim = false;
  }
  if ((base8 = this.options).ltrim == null) {
    base8.ltrim = false;
  }
  if ((base9 = this.options).rtrim == null) {
    base9.rtrim = false;
  }
  if ((base10 = this.options).auto_parse == null) {
    base10.auto_parse = false;
  }
  if ((base11 = this.options).auto_parse_date == null) {
    base11.auto_parse_date = false;
  }
  if ((base12 = this.options).relax == null) {
    base12.relax = false;
  }
  if ((base13 = this.options).relax_column_count == null) {
    base13.relax_column_count = false;
  }
  if ((base14 = this.options).skip_empty_lines == null) {
    base14.skip_empty_lines = false;
  }
  if ((base15 = this.options).max_limit_on_data_read == null) {
    base15.max_limit_on_data_read = 128000;
  }
  if ((base16 = this.options).skip_lines_with_empty_values == null) {
    base16.skip_lines_with_empty_values = false;
  }
  this.lines = 0;
  this.count = 0;
  this.skipped_line_count = 0;
  this.empty_line_count = 0;
  this.is_int = /^(\-|\+)?([1-9]+[0-9]*)$/;
  this.is_float = function(value) {
    return (value - parseFloat(value) + 1) >= 0;
  };
  this._ = {};
  this._.decoder = new StringDecoder();
  this._.quoting = false;
  this._.commenting = false;
  this._.field = null;
  this._.nextChar = null;
  this._.closingQuote = 0;
  this._.line = [];
  this._.chunks = [];
  this._.rawBuf = '';
  this._.buf = '';
  if (this.options.rowDelimiter) {
    this._.rowDelimiterLength = Math.max.apply(Math, this.options.rowDelimiter.map(function(v) {
      return v.length;
    }));
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.stringify"></a>[function <span class="apidocSignatureSpan">csv.</span>stringify ()](#apidoc.element.csv.stringify)
- description and source-code
```javascript
stringify = function () {
  var callback, chunks, data, options, stringifier;
  if (arguments.length === 3) {
    data = arguments[0];
    options = arguments[1];
    callback = arguments[2];
  } else if (arguments.length === 2) {
    if (Array.isArray(arguments[0])) {
      data = arguments[0];
    } else {
      options = arguments[0];
    }
    if (typeof arguments[1] === 'function') {
      callback = arguments[1];
    } else {
      options = arguments[1];
    }
  } else if (arguments.length === 1) {
    if (typeof arguments[0] === 'function') {
      callback = arguments[0];
    } else if (Array.isArray(arguments[0])) {
      data = arguments[0];
    } else {
      options = arguments[0];
    }
  }
  if (options == null) {
    options = {};
  }
  stringifier = new Stringifier(options);
  if (data) {
    process.nextTick(function() {
      var d, j, len;
      for (j = 0, len = data.length; j < len; j++) {
        d = data[j];
        stringifier.write(d);
      }
      return stringifier.end();
    });
  }
  if (callback) {
    chunks = [];
    stringifier.on('readable', function() {
      var chunk, results;
      results = [];
      while (chunk = stringifier.read()) {
        results.push(chunks.push(chunk));
      }
      return results;
    });
    stringifier.on('error', function(err) {
      return callback(err);
    });
    stringifier.on('end', function() {
      return callback(null, chunks.join(''));
    });
  }
  return stringifier;
}
```
- example usage
```shell
...
var csv = require('csv');

csv.generate({seed: 1, columns: 2, length: 20}, function(err, data){
  csv.parse(data, function(err, data){
    csv.transform(data, function(data){
      return data.map(function(value){return value.toUpperCase()});
    }, function(err, data){
      csv.stringify(data, function(err, data){
        process.stdout.write(data);
      });
    });
  });
});
'''
...
```

#### <a name="apidoc.element.csv.stringify.Stringifier"></a>[function <span class="apidocSignatureSpan">csv.</span>stringify.Stringifier (opts)](#apidoc.element.csv.stringify.Stringifier)
- description and source-code
```javascript
stringify.Stringifier = function (opts) {
  var base, base1, base10, base11, base12, base2, base3, base4, base5, base6, base7, base8, base9, k, options, v;
  if (opts == null) {
    opts = {};
  }
  options = {};
  for (k in opts) {
    v = opts[k];
    options[k] = v;
  }
  stream.Transform.call(this, options);
  this.options = options;
  if ((base = this.options).delimiter == null) {
    base.delimiter = ',';
  }
  if ((base1 = this.options).quote == null) {
    base1.quote = '"';
  }
  if ((base2 = this.options).quoted == null) {
    base2.quoted = false;
  }
  if ((base3 = this.options).quotedString == null) {
    base3.quotedString = false;
  }
  if ((base4 = this.options).eof == null) {
    base4.eof = true;
  }
  if ((base5 = this.options).escape == null) {
    base5.escape = '"';
  }
  if ((base6 = this.options).columns == null) {
    base6.columns = null;
  }
  if ((base7 = this.options).header == null) {
    base7.header = false;
  }
  if ((base8 = this.options).formatters == null) {
    base8.formatters = {};
  }
  if ((base9 = this.options.formatters).date == null) {
    base9.date = function(value) {
      return '' + value.getTime();
    };
  }
  if ((base10 = this.options.formatters).bool == null) {
    base10.bool = function(value) {
      if (value) {
        return '1';
      } else {
        return '';
      }
    };
  }
  if ((base11 = this.options.formatters).object == null) {
    base11.object = function(value) {
      return JSON.stringify(value);
    };
  }
  if ((base12 = this.options).rowDelimiter == null) {
    base12.rowDelimiter = '\n';
  }
  if (this.countWriten == null) {
    this.countWriten = 0;
  }
  switch (this.options.rowDelimiter) {
    case 'auto':
      this.options.rowDelimiter = null;
      break;
    case 'unix':
      this.options.rowDelimiter = "\n";
      break;
    case 'mac':
      this.options.rowDelimiter = "\r";
      break;
    case 'windows':
      this.options.rowDelimiter = "\r\n";
      break;
    case 'unicode':
      this.options.rowDelimiter = "\u2028";
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.transform"></a>[function <span class="apidocSignatureSpan">csv.</span>transform ()](#apidoc.element.csv.transform)
- description and source-code
```javascript
transform = function () {
  var argument, callback, data, error, handler, i, j, k, len, options, result, transform, type, v;
  options = {};
  for (i = j = 0, len = arguments.length; j < len; i = ++j) {
    argument = arguments[i];
    type = typeof argument;
    if (argument === null) {
      type = 'null';
    } else if (type === 'object' && Array.isArray(argument)) {
      type = 'array';
    }
    if (i === 0) {
      if (type === 'function') {
        handler = argument;
      } else if (type !== null) {
        data = argument;
      }
      continue;
    }
    if (type === 'object') {
      for (k in argument) {
        v = argument[k];
        options[k] = v;
      }
    } else if (type === 'function') {
      if (handler && i === arguments.length - 1) {
        callback = argument;
      } else {
        handler = argument;
      }
    } else if (type !== 'null') {
      throw new Error('Invalid arguments');
    }
  }
  transform = new Transformer(options, handler);
  error = false;
  if (data) {
    process.nextTick(function() {
      var len1, m, row;
      for (m = 0, len1 = data.length; m < len1; m++) {
        row = data[m];
        if (error) {
          break;
        }
        transform.write(row);
      }
      return transform.end();
    });
  }
  if (callback || options.consume) {
    result = [];
    transform.on('readable', function() {
      var r, results;
      results = [];
      while ((r = transform.read())) {
        if (callback) {
          results.push(result.push(r));
        } else {
          results.push(void 0);
        }
      }
      return results;
    });
    transform.on('error', function(err) {
      error = true;
      if (callback) {
        return callback(err);
      }
    });
    transform.on('end', function() {
      if (callback && !error) {
        return callback(null, result);
      }
    });
  }
  return transform;
}
```
- example usage
```shell
...
Execute this script with the command 'node samples/callback.js'.

'''javascript
var csv = require('csv');

csv.generate({seed: 1, columns: 2, length: 20}, function(err, data){
csv.parse(data, function(err, data){
  csv.transform(data, function(data){
    return data.map(function(value){return value.toUpperCase()});
  }, function(err, data){
    csv.stringify(data, function(err, data){
      process.stdout.write(data);
    });
  });
});
...
```

#### <a name="apidoc.element.csv.transform.Transformer"></a>[function <span class="apidocSignatureSpan">csv.</span>transform.Transformer (options1, transform1)](#apidoc.element.csv.transform.Transformer)
- description and source-code
```javascript
transform.Transformer = function (options1, transform1) {
  var base;
  this.options = options1 != null ? options1 : {};
  this.transform = transform1;
  this.options.objectMode = true;
  if ((base = this.options).parallel == null) {
    base.parallel = 100;
  }
  stream.Transform.call(this, this.options);
  this.running = 0;
  this.started = 0;
  this.finished = 0;
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.csv.generate"></a>[module csv.generate](#apidoc.module.csv.generate)

#### <a name="apidoc.element.csv.generate.generate"></a>[function <span class="apidocSignatureSpan">csv.</span>generate ()](#apidoc.element.csv.generate.generate)
- description and source-code
```javascript
generate = function () {
  var callback, data, generator, options;
  if (arguments.length === 2) {
    options = arguments[0];
    callback = arguments[1];
  } else if (arguments.length === 1) {
    if (typeof arguments[0] === 'function') {
      options = {};
      callback = arguments[0];
    } else {
      options = arguments[0];
    }
  } else if (arguments.length === 0) {
    options = {};
  }
  generator = new Generator(options);
  if (callback) {
    data = [];
    generator.on('readable', function() {
      var d, results;
      results = [];
      while (d = generator.read()) {
        results.push(data.push(options.objectMode ? d : d.toString()));
      }
      return results;
    });
    generator.on('error', callback);
    generator.on('end', function() {
      return callback(null, options.objectMode ? data : data.join(''));
    });
  }
  return generator;
}
```
- example usage
```shell
...
### Callback example

Execute this script with the command 'node samples/callback.js'.

'''javascript
var csv = require('csv');

csv.generate({seed: 1, columns: 2, length: 20}, function(err, data){
csv.parse(data, function(err, data){
  csv.transform(data, function(data){
    return data.map(function(value){return value.toUpperCase()});
  }, function(err, data){
    csv.stringify(data, function(err, data){
      process.stdout.write(data);
    });
...
```

#### <a name="apidoc.element.csv.generate.Generator"></a>[function <span class="apidocSignatureSpan">csv.generate.</span>Generator (options1)](#apidoc.element.csv.generate.Generator)
- description and source-code
```javascript
Generator = function (options1) {
  var base, base1, base2, base3, base4, base5, base6, base7, base8, i, j, len, ref, v;
  this.options = options1 != null ? options1 : {};
  stream.Readable.call(this, this.options);
  this.options.count = 0;
  if ((base = this.options).duration == null) {
    base.duration = 4 * 60 * 1000;
  }
  if ((base1 = this.options).columns == null) {
    base1.columns = 8;
  }
  if ((base2 = this.options).max_word_length == null) {
    base2.max_word_length = 16;
  }
  if ((base3 = this.options).fixed_size == null) {
    base3.fixed_size = false;
  }
  if (this.fixed_size_buffer == null) {
    this.fixed_size_buffer = '';
  }
  if ((base4 = this.options).start == null) {
    base4.start = Date.now();
  }
  if ((base5 = this.options).end == null) {
    base5.end = null;
  }
  if ((base6 = this.options).seed == null) {
    base6.seed = false;
  }
  if ((base7 = this.options).length == null) {
    base7.length = -1;
  }
  if ((base8 = this.options).delimiter == null) {
    base8.delimiter = ',';
  }
  this.count_written = 0;
  this.count_created = 0;
  if (typeof this.options.columns === 'number') {
    this.options.columns = new Array(this.options.columns);
  }
  ref = this.options.columns;
  for (i = j = 0, len = ref.length; j < len; i = ++j) {
    v = ref[i];
    if (v == null) {
      v = 'ascii';
    }
    if (typeof v === 'string') {
      this.options.columns[i] = Generator[v];
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.csv.generate.Generator"></a>[module csv.generate.Generator](#apidoc.module.csv.generate.Generator)

#### <a name="apidoc.element.csv.generate.Generator.Generator"></a>[function <span class="apidocSignatureSpan">csv.generate.</span>Generator (options1)](#apidoc.element.csv.generate.Generator.Generator)
- description and source-code
```javascript
Generator = function (options1) {
  var base, base1, base2, base3, base4, base5, base6, base7, base8, i, j, len, ref, v;
  this.options = options1 != null ? options1 : {};
  stream.Readable.call(this, this.options);
  this.options.count = 0;
  if ((base = this.options).duration == null) {
    base.duration = 4 * 60 * 1000;
  }
  if ((base1 = this.options).columns == null) {
    base1.columns = 8;
  }
  if ((base2 = this.options).max_word_length == null) {
    base2.max_word_length = 16;
  }
  if ((base3 = this.options).fixed_size == null) {
    base3.fixed_size = false;
  }
  if (this.fixed_size_buffer == null) {
    this.fixed_size_buffer = '';
  }
  if ((base4 = this.options).start == null) {
    base4.start = Date.now();
  }
  if ((base5 = this.options).end == null) {
    base5.end = null;
  }
  if ((base6 = this.options).seed == null) {
    base6.seed = false;
  }
  if ((base7 = this.options).length == null) {
    base7.length = -1;
  }
  if ((base8 = this.options).delimiter == null) {
    base8.delimiter = ',';
  }
  this.count_written = 0;
  this.count_created = 0;
  if (typeof this.options.columns === 'number') {
    this.options.columns = new Array(this.options.columns);
  }
  ref = this.options.columns;
  for (i = j = 0, len = ref.length; j < len; i = ++j) {
    v = ref[i];
    if (v == null) {
      v = 'ascii';
    }
    if (typeof v === 'string') {
      this.options.columns[i] = Generator[v];
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.generate.Generator.ascii"></a>[function <span class="apidocSignatureSpan">csv.generate.Generator.</span>ascii (gen)](#apidoc.element.csv.generate.Generator.ascii)
- description and source-code
```javascript
ascii = function (gen) {
  var char, column, j, nb_chars, ref;
  column = [];
  for (nb_chars = j = 0, ref = Math.ceil(gen.random() * gen.options.max_word_length); 0 <= ref ? j < ref : j > ref; nb_chars = 0
 <= ref ? ++j : --j) {
    char = Math.floor(gen.random() * 32);
    column.push(String.fromCharCode(char + (char < 16 ? 65 : 97 - 16)));
  }
  return column.join('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.generate.Generator.bool"></a>[function <span class="apidocSignatureSpan">csv.generate.Generator.</span>bool (gen)](#apidoc.element.csv.generate.Generator.bool)
- description and source-code
```javascript
bool = function (gen) {
  return Math.floor(gen.random() * 2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.generate.Generator.int"></a>[function <span class="apidocSignatureSpan">csv.generate.Generator.</span>int (gen)](#apidoc.element.csv.generate.Generator.int)
- description and source-code
```javascript
int = function (gen) {
  return Math.floor(gen.random() * Math.pow(2, 52));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.generate.Generator.super_"></a>[function <span class="apidocSignatureSpan">csv.generate.Generator.</span>super_ (options)](#apidoc.element.csv.generate.Generator.super_)
- description and source-code
```javascript
function Readable(options) {
  if (!(this instanceof Readable))
    return new Readable(options);

  this._readableState = new ReadableState(options, this);

  // legacy
  this.readable = true;

  if (options && typeof options.read === 'function')
    this._read = options.read;

  Stream.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.csv.generate.Generator.prototype"></a>[module csv.generate.Generator.prototype](#apidoc.module.csv.generate.Generator.prototype)

#### <a name="apidoc.element.csv.generate.Generator.prototype._read"></a>[function <span class="apidocSignatureSpan">csv.generate.Generator.prototype.</span>_read (size)](#apidoc.element.csv.generate.Generator.prototype._read)
- description and source-code
```javascript
_read = function (size) {
  var column, data, header, j, k, l, len, len1, len2, len3, length, line, lineLength, m, ref;
  data = [];
  length = this.fixed_size_buffer.length;
  if (length) {
    data.push(this.fixed_size_buffer);
  }
  while (true) {
    if ((this.count_created === this.options.length) || (this.options.end && Date.now() > this.options.end)) {
      if (data.length) {
        if (this.options.objectMode) {
          for (j = 0, len = data.length; j < len; j++) {
            line = data[j];
            this.count_written++;
            this.push(line);
          }
        } else {
          this.count_written++;
          this.push(data.join(''));
        }
      }
      return this.push(null);
    }
    line = [];
    ref = this.options.columns;
    for (k = 0, len1 = ref.length; k < len1; k++) {
      header = ref[k];
      line.push("" + (header(this)));
    }
    if (this.options.objectMode) {
      lineLength = 0;
      for (l = 0, len2 = line.length; l < len2; l++) {
        column = line[l];
        lineLength += column.length;
      }
    } else {
      line = "" + (this.count_created === 0 ? '' : '\n') + (line.join(this.options.delimiter));
      lineLength = line.length;
    }
    this.count_created++;
    if (length + lineLength > size) {
      if (this.options.objectMode) {
        data.push(line);
        for (m = 0, len3 = data.length; m < len3; m++) {
          line = data[m];
          this.count_written++;
          this.push(line);
        }
      } else {
        if (this.options.fixed_size) {
          this.fixed_size_buffer = line.substr(size - length);
          data.push(line.substr(0, size - length));
        } else {
          data.push(line);
        }
        this.count_written++;
        this.push(data.join(''));
      }
      break;
    }
    length += lineLength;
    data.push(line);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.generate.Generator.prototype.end"></a>[function <span class="apidocSignatureSpan">csv.generate.Generator.prototype.</span>end ()](#apidoc.element.csv.generate.Generator.prototype.end)
- description and source-code
```javascript
end = function () {
  return this.push(null);
}
```
- example usage
```shell
...

generator.on('readable', function(){
  while(data = generator.read()){
    parser.write(data);
  }
});
generator.on('end', function(){
  parser.end()
});

parser.on('readable', function(){
  while(data = parser.read()){
    transformer.write(data);
  }
});
...
```

#### <a name="apidoc.element.csv.generate.Generator.prototype.random"></a>[function <span class="apidocSignatureSpan">csv.generate.Generator.prototype.</span>random ()](#apidoc.element.csv.generate.Generator.prototype.random)
- description and source-code
```javascript
random = function () {
  if (this.options.seed) {
    return this.options.seed = this.options.seed * Math.PI * 100 % 100 / 100;
  } else {
    return Math.random();
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.csv.parse"></a>[module csv.parse](#apidoc.module.csv.parse)

#### <a name="apidoc.element.csv.parse.parse"></a>[function <span class="apidocSignatureSpan">csv.</span>parse ()](#apidoc.element.csv.parse.parse)
- description and source-code
```javascript
parse = function () {
  var callback, called, chunks, data, options, parser;
  if (arguments.length === 3) {
    data = arguments[0];
    options = arguments[1];
    callback = arguments[2];
    if (typeof callback !== 'function') {
      throw Error("Invalid callback argument: " + (JSON.stringify(callback)));
    }
    if (!(typeof data === 'string' || Buffer.isBuffer(arguments[0]))) {
      return callback(Error("Invalid data argument: " + (JSON.stringify(data))));
    }
  } else if (arguments.length === 2) {
    if (typeof arguments[0] === 'string' || Buffer.isBuffer(arguments[0])) {
      data = arguments[0];
    } else {
      options = arguments[0];
    }
    if (typeof arguments[1] === 'function') {
      callback = arguments[1];
    } else {
      options = arguments[1];
    }
  } else if (arguments.length === 1) {
    if (typeof arguments[0] === 'function') {
      callback = arguments[0];
    } else {
      options = arguments[0];
    }
  }
  if (options == null) {
    options = {};
  }
  parser = new Parser(options);
  if (data != null) {
    process.nextTick(function() {
      parser.write(data);
      return parser.end();
    });
  }
  if (callback) {
    called = false;
    chunks = options.objname ? {} : [];
    parser.on('readable', function() {
      var chunk, results;
      results = [];
      while (chunk = parser.read()) {
        if (options.objname) {
          results.push(chunks[chunk[0]] = chunk[1]);
        } else {
          results.push(chunks.push(chunk));
        }
      }
      return results;
    });
    parser.on('error', function(err) {
      called = true;
      return callback(err);
    });
    parser.on('end', function() {
      if (!called) {
        return callback(null, chunks);
      }
    });
  }
  return parser;
}
```
- example usage
```shell
...

Execute this script with the command 'node samples/callback.js'.

'''javascript
var csv = require('csv');

csv.generate({seed: 1, columns: 2, length: 20}, function(err, data){
csv.parse(data, function(err, data){
  csv.transform(data, function(data){
    return data.map(function(value){return value.toUpperCase()});
  }, function(err, data){
    csv.stringify(data, function(err, data){
      process.stdout.write(data);
    });
  });
...
```

#### <a name="apidoc.element.csv.parse.Parser"></a>[function <span class="apidocSignatureSpan">csv.parse.</span>Parser (options)](#apidoc.element.csv.parse.Parser)
- description and source-code
```javascript
Parser = function (options) {
  var base, base1, base10, base11, base12, base13, base14, base15, base16, base2, base3, base4, base5, base6, base7, base8, base9
, k, v;
  if (options == null) {
    options = {};
  }
  options.objectMode = true;
  this.options = {};
  for (k in options) {
    v = options[k];
    this.options[k] = v;
  }
  stream.Transform.call(this, this.options);
  if ((base = this.options).rowDelimiter == null) {
    base.rowDelimiter = null;
  }
  if (typeof this.options.rowDelimiter === 'string') {
    this.options.rowDelimiter = [this.options.rowDelimiter];
  }
  if ((base1 = this.options).delimiter == null) {
    base1.delimiter = ',';
  }
  if ((base2 = this.options).quote == null) {
    base2.quote = '"';
  }
  if ((base3 = this.options).escape == null) {
    base3.escape = '"';
  }
  if ((base4 = this.options).columns == null) {
    base4.columns = null;
  }
  if ((base5 = this.options).comment == null) {
    base5.comment = '';
  }
  if ((base6 = this.options).objname == null) {
    base6.objname = false;
  }
  if ((base7 = this.options).trim == null) {
    base7.trim = false;
  }
  if ((base8 = this.options).ltrim == null) {
    base8.ltrim = false;
  }
  if ((base9 = this.options).rtrim == null) {
    base9.rtrim = false;
  }
  if ((base10 = this.options).auto_parse == null) {
    base10.auto_parse = false;
  }
  if ((base11 = this.options).auto_parse_date == null) {
    base11.auto_parse_date = false;
  }
  if ((base12 = this.options).relax == null) {
    base12.relax = false;
  }
  if ((base13 = this.options).relax_column_count == null) {
    base13.relax_column_count = false;
  }
  if ((base14 = this.options).skip_empty_lines == null) {
    base14.skip_empty_lines = false;
  }
  if ((base15 = this.options).max_limit_on_data_read == null) {
    base15.max_limit_on_data_read = 128000;
  }
  if ((base16 = this.options).skip_lines_with_empty_values == null) {
    base16.skip_lines_with_empty_values = false;
  }
  this.lines = 0;
  this.count = 0;
  this.skipped_line_count = 0;
  this.empty_line_count = 0;
  this.is_int = /^(\-|\+)?([1-9]+[0-9]*)$/;
  this.is_float = function(value) {
    return (value - parseFloat(value) + 1) >= 0;
  };
  this._ = {};
  this._.decoder = new StringDecoder();
  this._.quoting = false;
  this._.commenting = false;
  this._.field = null;
  this._.nextChar = null;
  this._.closingQuote = 0;
  this._.line = [];
  this._.chunks = [];
  this._.rawBuf = '';
  this._.buf = '';
  if (this.options.rowDelimiter) {
    this._.rowDelimiterLength = Math.max.apply(Math, this.options.rowDelimiter.map(function(v) {
      return v.length;
    }));
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.csv.parse.Parser"></a>[module csv.parse.Parser](#apidoc.module.csv.parse.Parser)

#### <a name="apidoc.element.csv.parse.Parser.Parser"></a>[function <span class="apidocSignatureSpan">csv.parse.</span>Parser (options)](#apidoc.element.csv.parse.Parser.Parser)
- description and source-code
```javascript
Parser = function (options) {
  var base, base1, base10, base11, base12, base13, base14, base15, base16, base2, base3, base4, base5, base6, base7, base8, base9
, k, v;
  if (options == null) {
    options = {};
  }
  options.objectMode = true;
  this.options = {};
  for (k in options) {
    v = options[k];
    this.options[k] = v;
  }
  stream.Transform.call(this, this.options);
  if ((base = this.options).rowDelimiter == null) {
    base.rowDelimiter = null;
  }
  if (typeof this.options.rowDelimiter === 'string') {
    this.options.rowDelimiter = [this.options.rowDelimiter];
  }
  if ((base1 = this.options).delimiter == null) {
    base1.delimiter = ',';
  }
  if ((base2 = this.options).quote == null) {
    base2.quote = '"';
  }
  if ((base3 = this.options).escape == null) {
    base3.escape = '"';
  }
  if ((base4 = this.options).columns == null) {
    base4.columns = null;
  }
  if ((base5 = this.options).comment == null) {
    base5.comment = '';
  }
  if ((base6 = this.options).objname == null) {
    base6.objname = false;
  }
  if ((base7 = this.options).trim == null) {
    base7.trim = false;
  }
  if ((base8 = this.options).ltrim == null) {
    base8.ltrim = false;
  }
  if ((base9 = this.options).rtrim == null) {
    base9.rtrim = false;
  }
  if ((base10 = this.options).auto_parse == null) {
    base10.auto_parse = false;
  }
  if ((base11 = this.options).auto_parse_date == null) {
    base11.auto_parse_date = false;
  }
  if ((base12 = this.options).relax == null) {
    base12.relax = false;
  }
  if ((base13 = this.options).relax_column_count == null) {
    base13.relax_column_count = false;
  }
  if ((base14 = this.options).skip_empty_lines == null) {
    base14.skip_empty_lines = false;
  }
  if ((base15 = this.options).max_limit_on_data_read == null) {
    base15.max_limit_on_data_read = 128000;
  }
  if ((base16 = this.options).skip_lines_with_empty_values == null) {
    base16.skip_lines_with_empty_values = false;
  }
  this.lines = 0;
  this.count = 0;
  this.skipped_line_count = 0;
  this.empty_line_count = 0;
  this.is_int = /^(\-|\+)?([1-9]+[0-9]*)$/;
  this.is_float = function(value) {
    return (value - parseFloat(value) + 1) >= 0;
  };
  this._ = {};
  this._.decoder = new StringDecoder();
  this._.quoting = false;
  this._.commenting = false;
  this._.field = null;
  this._.nextChar = null;
  this._.closingQuote = 0;
  this._.line = [];
  this._.chunks = [];
  this._.rawBuf = '';
  this._.buf = '';
  if (this.options.rowDelimiter) {
    this._.rowDelimiterLength = Math.max.apply(Math, this.options.rowDelimiter.map(function(v) {
      return v.length;
    }));
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.parse.Parser.super_"></a>[function <span class="apidocSignatureSpan">csv.parse.Parser.</span>super_ (options)](#apidoc.element.csv.parse.Parser.super_)
- description and source-code
```javascript
function Transform(options) {
  if (!(this instanceof Transform))
    return new Transform(options);

  Duplex.call(this, options);

  this._transformState = new TransformState(this);

  var stream = this;

  // start out asking for a readable event once data is transformed.
  this._readableState.needReadable = true;

  // we have implemented the _read method, and done the other things
  // that Readable wants before the first _read call, so unset the
  // sync guard flag.
  this._readableState.sync = false;

  if (options) {
    if (typeof options.transform === 'function')
      this._transform = options.transform;

    if (typeof options.flush === 'function')
      this._flush = options.flush;
  }

  // When the writable side finishes, then flush out anything remaining.
  this.once('prefinish', function() {
    if (typeof this._flush === 'function')
      this._flush(function(er) {
        done(stream, er);
      });
    else
      done(stream);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.csv.parse.Parser.prototype"></a>[module csv.parse.Parser.prototype](#apidoc.module.csv.parse.Parser.prototype)

#### <a name="apidoc.element.csv.parse.Parser.prototype.__push"></a>[function <span class="apidocSignatureSpan">csv.parse.Parser.prototype.</span>__push (line)](#apidoc.element.csv.parse.Parser.prototype.__push)
- description and source-code
```javascript
__push = function (line) {
  var field, i, j, len, lineAsColumns, rawBuf, row;
  if (this.options.skip_lines_with_empty_values && line.join('').trim() === '') {
    return;
  }
  row = null;
  if (this.options.columns === true) {
    this.options.columns = line;
    rawBuf = '';
    return;
  } else if (typeof this.options.columns === 'function') {
    this.options.columns = this.options.columns(line);
    rawBuf = '';
    return;
  }
  if (!this._.line_length && line.length > 0) {
    this._.line_length = this.options.columns ? this.options.columns.length : line.length;
  }
  if (line.length === 1 && line[0] === '') {
    this.empty_line_count++;
  } else if (line.length !== this._.line_length) {
    if (this.options.relax_column_count) {
      this.skipped_line_count++;
    } else if (this.options.columns != null) {
      throw Error("Number of columns on line " + this.lines + " does not match header");
    } else {
      throw Error("Number of columns is inconsistent on line " + this.lines);
    }
  } else {
    this.count++;
  }
  if (this.options.columns != null) {
    lineAsColumns = {};
    for (i = j = 0, len = line.length; j < len; i = ++j) {
      field = line[i];
      if (this.options.columns[i] === false) {
        continue;
      }
      lineAsColumns[this.options.columns[i]] = field;
    }
    if (this.options.objname) {
      row = [lineAsColumns[this.options.objname], lineAsColumns];
    } else {
      row = lineAsColumns;
    }
  } else {
    row = line;
  }
  if (this.count < this.options.from) {
    return;
  }
  if (this.count > this.options.to) {
    return;
  }
  if (this.options.raw) {
    this.push({
      raw: this._.rawBuf,
      row: row
    });
    return this._.rawBuf = '';
  } else {
    return this.push(row);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.parse.Parser.prototype.__write"></a>[function <span class="apidocSignatureSpan">csv.parse.Parser.prototype.</span>__write (chars, end)](#apidoc.element.csv.parse.Parser.prototype.__write)
- description and source-code
```javascript
__write = function (chars, end) {
  var areNextCharsDelimiter, areNextCharsRowDelimiters, auto_parse, char, escapeIsQuote, i, isDelimiter, isEscape, isNextCharAComment
, isQuote, isRowDelimiter, isRowDelimiterLength, is_float, is_int, l, ltrim, nextCharPos, ref, ref1, ref2, ref3, ref4, remainingBuffer
, results, rowDelimiter, rtrim, wasCommenting;
  is_int = (function(_this) {
    return function(value) {
      if (typeof _this.is_int === 'function') {
        return _this.is_int(value);
      } else {
        return _this.is_int.test(value);
      }
    };
  })(this);
  is_float = (function(_this) {
    return function(value) {
      if (typeof _this.is_float === 'function') {
        return _this.is_float(value);
      } else {
        return _this.is_float.test(value);
      }
    };
  })(this);
  auto_parse = (function(_this) {
    return function(value) {
      var m;
      if (!_this.options.auto_parse) {
        return value;
      }
      if (is_int(value)) {
        value = parseInt(value);
      } else if (is_float(value)) {
        value = parseFloat(value);
      } else if (_this.options.auto_parse_date) {
        m = Date.parse(value);
        if (!isNaN(m)) {
          value = new Date(m);
        }
      }
      return value;
    };
  })(this);
  ltrim = this.options.trim || this.options.ltrim;
  rtrim = this.options.trim || this.options.rtrim;
  chars = this._.buf + chars;
  l = chars.length;
  i = 0;
  if (this.lines === 0 && 0xFEFF === chars.charCodeAt(0)) {
    i++;
  }
  while (i < l) {
    if (!end) {
      remainingBuffer = chars.substr(i, l - i);
      if ((!this.options.rowDelimiter && i + 3 > l) || (!this._.commenting && l - i < this.options.comment.length && this.options
.comment.substr(0, l - i) === remainingBuffer) || (this.options.rowDelimiter && l - i < this._.rowDelimiterLength && this.options
.rowDelimiter.some(function(rd) {
        return rd.substr(0, l - i) === remainingBuffer;
      })) || (this.options.rowDelimiter && this._.quoting && l - i < (this.options.quote.length + this._.rowDelimiterLength) &&
this.options.rowDelimiter.some((function(_this) {
        return function(rd) {
          return (_this.options.quote + rd).substr(0, l - i) === remainingBuffer;
        };
      })(this))) || (l - i <= this.options.delimiter.length && this.options.delimiter.substr(0, l - i) === remainingBuffer) || (
l - i <= this.options.escape.length && this.options.escape.substr(0, l - i) === remainingBuffer)) {
        break;
      }
    }
    char = this._.nextChar ? this._.nextChar : chars.charAt(i);
    this._.nextChar = l > i + 1 ? chars.charAt(i + 1) : '';
    if (this.options.raw) {
      this._.rawBuf += char;
    }
    if (this.options.rowDelimiter == null) {
      nextCharPos = i;
      rowDelimiter = null;
      if (!this._.quoting && (char === '\n' || char === '\r')) {
        rowDelimiter = char;
        nextCharPos += 1;
      } else if (!(!this._.quoting && char === this.options.quote) && (this._.nextChar === '\n' || this._.nextChar === '\r')) {
        rowDelimiter = this._.nextChar;
        nextCharPos += 2;
        if (this.raw) {
          rawBuf += this._.nextChar;
        }
      }
      if (rowDelimiter) {
        if (rowDelimiter === '\r' && chars.charAt(nextCharPos) === '\n') {
          rowDelimiter += '\n';
        }
        this.options.rowDelimiter = [rowDelimiter];
        this._.rowDelimiterLength = rowDelimiter.length;
      }
    }
    if (!this._.commenting && char === this.options.escape) {
      escapeIsQuote = this.options.escape === this.options.quote;
      isEscape = this._.nextChar === this.options.escape;
      isQuote = this._.nextChar === this.options.quote;
      if (!(escapeIsQuote && (this._.field == null) && !this._.quoting) && (isEscape || isQuote)) {
        i++;
        char = this._.nextChar;
        this._.nextChar = chars.charAt(i + 1);
        if (this._.field == null) {
          this._.field = '';
        }
        this._.field += char;
        if (this.options.raw) {
          this._.rawBuf += char;
        }
        i++;
        continue;
      }
    } ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.parse.Parser.prototype._flush"></a>[function <span class="apidocSignatureSpan">csv.parse.Parser.prototype.</span>_flush (callback)](#apidoc.element.csv.parse.Parser.prototype._flush)
- description and source-code
```javascript
_flush = function (callback) {
  var err, error;
  try {
    this.__write(this._.decoder.end(), true);
    if (this._.quoting) {
      this.emit('error', new Error("Quoted field not terminated at line " + (this.lines + 1)));
      return;
    }
    if (this._.line.length > 0) {
      this.__push(this._.line);
    }
    return callback();
  } catch (error) {
    err = error;
    return this.emit('error', err);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.parse.Parser.prototype._transform"></a>[function <span class="apidocSignatureSpan">csv.parse.Parser.prototype.</span>_transform (chunk, encoding, callback)](#apidoc.element.csv.parse.Parser.prototype._transform)
- description and source-code
```javascript
_transform = function (chunk, encoding, callback) {
  var err, error;
  if (chunk instanceof Buffer) {
    chunk = this._.decoder.write(chunk);
  }
  try {
    this.__write(chunk, false);
    return callback();
  } catch (error) {
    err = error;
    return this.emit('error', err);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.csv.stringify"></a>[module csv.stringify](#apidoc.module.csv.stringify)

#### <a name="apidoc.element.csv.stringify.stringify"></a>[function <span class="apidocSignatureSpan">csv.</span>stringify ()](#apidoc.element.csv.stringify.stringify)
- description and source-code
```javascript
stringify = function () {
  var callback, chunks, data, options, stringifier;
  if (arguments.length === 3) {
    data = arguments[0];
    options = arguments[1];
    callback = arguments[2];
  } else if (arguments.length === 2) {
    if (Array.isArray(arguments[0])) {
      data = arguments[0];
    } else {
      options = arguments[0];
    }
    if (typeof arguments[1] === 'function') {
      callback = arguments[1];
    } else {
      options = arguments[1];
    }
  } else if (arguments.length === 1) {
    if (typeof arguments[0] === 'function') {
      callback = arguments[0];
    } else if (Array.isArray(arguments[0])) {
      data = arguments[0];
    } else {
      options = arguments[0];
    }
  }
  if (options == null) {
    options = {};
  }
  stringifier = new Stringifier(options);
  if (data) {
    process.nextTick(function() {
      var d, j, len;
      for (j = 0, len = data.length; j < len; j++) {
        d = data[j];
        stringifier.write(d);
      }
      return stringifier.end();
    });
  }
  if (callback) {
    chunks = [];
    stringifier.on('readable', function() {
      var chunk, results;
      results = [];
      while (chunk = stringifier.read()) {
        results.push(chunks.push(chunk));
      }
      return results;
    });
    stringifier.on('error', function(err) {
      return callback(err);
    });
    stringifier.on('end', function() {
      return callback(null, chunks.join(''));
    });
  }
  return stringifier;
}
```
- example usage
```shell
...
var csv = require('csv');

csv.generate({seed: 1, columns: 2, length: 20}, function(err, data){
  csv.parse(data, function(err, data){
    csv.transform(data, function(data){
      return data.map(function(value){return value.toUpperCase()});
    }, function(err, data){
      csv.stringify(data, function(err, data){
        process.stdout.write(data);
      });
    });
  });
});
'''
...
```

#### <a name="apidoc.element.csv.stringify.Stringifier"></a>[function <span class="apidocSignatureSpan">csv.stringify.</span>Stringifier (opts)](#apidoc.element.csv.stringify.Stringifier)
- description and source-code
```javascript
Stringifier = function (opts) {
  var base, base1, base10, base11, base12, base2, base3, base4, base5, base6, base7, base8, base9, k, options, v;
  if (opts == null) {
    opts = {};
  }
  options = {};
  for (k in opts) {
    v = opts[k];
    options[k] = v;
  }
  stream.Transform.call(this, options);
  this.options = options;
  if ((base = this.options).delimiter == null) {
    base.delimiter = ',';
  }
  if ((base1 = this.options).quote == null) {
    base1.quote = '"';
  }
  if ((base2 = this.options).quoted == null) {
    base2.quoted = false;
  }
  if ((base3 = this.options).quotedString == null) {
    base3.quotedString = false;
  }
  if ((base4 = this.options).eof == null) {
    base4.eof = true;
  }
  if ((base5 = this.options).escape == null) {
    base5.escape = '"';
  }
  if ((base6 = this.options).columns == null) {
    base6.columns = null;
  }
  if ((base7 = this.options).header == null) {
    base7.header = false;
  }
  if ((base8 = this.options).formatters == null) {
    base8.formatters = {};
  }
  if ((base9 = this.options.formatters).date == null) {
    base9.date = function(value) {
      return '' + value.getTime();
    };
  }
  if ((base10 = this.options.formatters).bool == null) {
    base10.bool = function(value) {
      if (value) {
        return '1';
      } else {
        return '';
      }
    };
  }
  if ((base11 = this.options.formatters).object == null) {
    base11.object = function(value) {
      return JSON.stringify(value);
    };
  }
  if ((base12 = this.options).rowDelimiter == null) {
    base12.rowDelimiter = '\n';
  }
  if (this.countWriten == null) {
    this.countWriten = 0;
  }
  switch (this.options.rowDelimiter) {
    case 'auto':
      this.options.rowDelimiter = null;
      break;
    case 'unix':
      this.options.rowDelimiter = "\n";
      break;
    case 'mac':
      this.options.rowDelimiter = "\r";
      break;
    case 'windows':
      this.options.rowDelimiter = "\r\n";
      break;
    case 'unicode':
      this.options.rowDelimiter = "\u2028";
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.csv.stringify.Stringifier"></a>[module csv.stringify.Stringifier](#apidoc.module.csv.stringify.Stringifier)

#### <a name="apidoc.element.csv.stringify.Stringifier.Stringifier"></a>[function <span class="apidocSignatureSpan">csv.stringify.</span>Stringifier (opts)](#apidoc.element.csv.stringify.Stringifier.Stringifier)
- description and source-code
```javascript
Stringifier = function (opts) {
  var base, base1, base10, base11, base12, base2, base3, base4, base5, base6, base7, base8, base9, k, options, v;
  if (opts == null) {
    opts = {};
  }
  options = {};
  for (k in opts) {
    v = opts[k];
    options[k] = v;
  }
  stream.Transform.call(this, options);
  this.options = options;
  if ((base = this.options).delimiter == null) {
    base.delimiter = ',';
  }
  if ((base1 = this.options).quote == null) {
    base1.quote = '"';
  }
  if ((base2 = this.options).quoted == null) {
    base2.quoted = false;
  }
  if ((base3 = this.options).quotedString == null) {
    base3.quotedString = false;
  }
  if ((base4 = this.options).eof == null) {
    base4.eof = true;
  }
  if ((base5 = this.options).escape == null) {
    base5.escape = '"';
  }
  if ((base6 = this.options).columns == null) {
    base6.columns = null;
  }
  if ((base7 = this.options).header == null) {
    base7.header = false;
  }
  if ((base8 = this.options).formatters == null) {
    base8.formatters = {};
  }
  if ((base9 = this.options.formatters).date == null) {
    base9.date = function(value) {
      return '' + value.getTime();
    };
  }
  if ((base10 = this.options.formatters).bool == null) {
    base10.bool = function(value) {
      if (value) {
        return '1';
      } else {
        return '';
      }
    };
  }
  if ((base11 = this.options.formatters).object == null) {
    base11.object = function(value) {
      return JSON.stringify(value);
    };
  }
  if ((base12 = this.options).rowDelimiter == null) {
    base12.rowDelimiter = '\n';
  }
  if (this.countWriten == null) {
    this.countWriten = 0;
  }
  switch (this.options.rowDelimiter) {
    case 'auto':
      this.options.rowDelimiter = null;
      break;
    case 'unix':
      this.options.rowDelimiter = "\n";
      break;
    case 'mac':
      this.options.rowDelimiter = "\r";
      break;
    case 'windows':
      this.options.rowDelimiter = "\r\n";
      break;
    case 'unicode':
      this.options.rowDelimiter = "\u2028";
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.stringify.Stringifier.super_"></a>[function <span class="apidocSignatureSpan">csv.stringify.Stringifier.</span>super_ (options)](#apidoc.element.csv.stringify.Stringifier.super_)
- description and source-code
```javascript
function Transform(options) {
  if (!(this instanceof Transform))
    return new Transform(options);

  Duplex.call(this, options);

  this._transformState = new TransformState(this);

  var stream = this;

  // start out asking for a readable event once data is transformed.
  this._readableState.needReadable = true;

  // we have implemented the _read method, and done the other things
  // that Readable wants before the first _read call, so unset the
  // sync guard flag.
  this._readableState.sync = false;

  if (options) {
    if (typeof options.transform === 'function')
      this._transform = options.transform;

    if (typeof options.flush === 'function')
      this._flush = options.flush;
  }

  // When the writable side finishes, then flush out anything remaining.
  this.once('prefinish', function() {
    if (typeof this._flush === 'function')
      this._flush(function(er) {
        done(stream, er);
      });
    else
      done(stream);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.csv.stringify.Stringifier.prototype"></a>[module csv.stringify.Stringifier.prototype](#apidoc.module.csv.stringify.Stringifier.prototype)

#### <a name="apidoc.element.csv.stringify.Stringifier.prototype._transform"></a>[function <span class="apidocSignatureSpan">csv.stringify.Stringifier.prototype.</span>_transform (chunk, encoding, callback)](#apidoc.element.csv.stringify.Stringifier.prototype._transform)
- description and source-code
```javascript
_transform = function (chunk, encoding, callback) {
  this.push(chunk);
  return callback();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.stringify.Stringifier.prototype.end"></a>[function <span class="apidocSignatureSpan">csv.stringify.Stringifier.prototype.</span>end (chunk, encoding, callback)](#apidoc.element.csv.stringify.Stringifier.prototype.end)
- description and source-code
```javascript
end = function (chunk, encoding, callback) {
  if (this.countWriten === 0) {
    this.headers();
  }
  return stream.Transform.prototype.end.apply(this, arguments);
}
```
- example usage
```shell
...

generator.on('readable', function(){
  while(data = generator.read()){
    parser.write(data);
  }
});
generator.on('end', function(){
  parser.end()
});

parser.on('readable', function(){
  while(data = parser.read()){
    transformer.write(data);
  }
});
...
```

#### <a name="apidoc.element.csv.stringify.Stringifier.prototype.headers"></a>[function <span class="apidocSignatureSpan">csv.stringify.Stringifier.prototype.</span>headers ()](#apidoc.element.csv.stringify.Stringifier.prototype.headers)
- description and source-code
```javascript
headers = function () {
  var k, label, labels;
  if (!this.options.header) {
    return;
  }
  if (!this.options.columns) {
    return;
  }
  labels = this.options.columns;
  if (typeof labels === 'object') {
    labels = (function() {
      var results;
      results = [];
      for (k in labels) {
        label = labels[k];
        results.push(label);
      }
      return results;
    })();
  }
  if (this.options.eof) {
    labels = this.stringify(labels) + this.options.rowDelimiter;
  } else {
    labels = this.stringify(labels);
  }
  return stream.Transform.prototype.write.call(this, labels);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.stringify.Stringifier.prototype.stringify"></a>[function <span class="apidocSignatureSpan">csv.stringify.Stringifier.prototype.</span>stringify (line)](#apidoc.element.csv.stringify.Stringifier.prototype.stringify)
- description and source-code
```javascript
stringify = function (line) {
  var _line, column, columns, containsEscape, containsLinebreak, containsQuote, containsdelimiter, delimiter, escape, field, i,
j, l, newLine, quote, ref, ref1, regexp, shouldQuote, value;
  if (typeof line !== 'object') {
    return line;
  }
  columns = this.options.columns;
  if (typeof columns === 'object' && columns !== null && !Array.isArray(columns)) {
    columns = Object.keys(columns);
  }
  delimiter = this.options.delimiter;
  quote = this.options.quote;
  escape = this.options.escape;
  if (!Array.isArray(line)) {
    _line = [];
    if (columns) {
      for (i = j = 0, ref = columns.length; 0 <= ref ? j < ref : j > ref; i = 0 <= ref ? ++j : --j) {
        column = columns[i];
        value = get(line, column);
        _line[i] = typeof value === 'undefined' || value === null ? '' : value;
      }
    } else {
      for (column in line) {
        _line.push(line[column]);
      }
    }
    line = _line;
    _line = null;
  } else if (columns) {
    line.splice(columns.length);
  }
  if (Array.isArray(line)) {
    newLine = '';
    for (i = l = 0, ref1 = line.length; 0 <= ref1 ? l < ref1 : l > ref1; i = 0 <= ref1 ? ++l : --l) {
      field = line[i];
      if (typeof field === 'string') {

      } else if (typeof field === 'number') {
        field = '' + field;
      } else if (typeof field === 'boolean') {
        field = this.options.formatters.bool(field);
      } else if (field instanceof Date) {
        field = this.options.formatters.date(field);
      } else if (typeof field === 'object' && field !== null) {
        field = this.options.formatters.object(field);
      }
      if (field) {
        containsdelimiter = field.indexOf(delimiter) >= 0;
        containsQuote = field.indexOf(quote) >= 0;
        containsEscape = field.indexOf(escape) >= 0 && (escape !== quote);
        containsLinebreak = field.indexOf('\r') >= 0 || field.indexOf('\n') >= 0;
        shouldQuote = containsQuote || containsdelimiter || containsLinebreak || this.options.quoted || (this.options.quotedString
 && typeof line[i] === 'string');
        if (shouldQuote && containsEscape) {
          regexp = escape === '\\' ? new RegExp(escape + escape, 'g') : new RegExp(escape, 'g');
          field = field.replace(regexp, escape + escape);
        }
        if (containsQuote) {
          regexp = new RegExp(quote, 'g');
          field = field.replace(regexp, escape + quote);
        }
        if (shouldQuote) {
          field = quote + field + quote;
        }
        newLine += field;
      } else if (this.options.quotedEmpty || ((this.options.quotedEmpty == null) && line[i] === '' && this.options.quotedString)) {
        newLine += quote + quote;
      }
      if (i !== line.length - 1) {
        newLine += delimiter;
      }
    }
    line = newLine;
  }
  return line;
}
```
- example usage
```shell
...
var csv = require('csv');

csv.generate({seed: 1, columns: 2, length: 20}, function(err, data){
  csv.parse(data, function(err, data){
    csv.transform(data, function(data){
      return data.map(function(value){return value.toUpperCase()});
    }, function(err, data){
      csv.stringify(data, function(err, data){
        process.stdout.write(data);
      });
    });
  });
});
'''
...
```

#### <a name="apidoc.element.csv.stringify.Stringifier.prototype.write"></a>[function <span class="apidocSignatureSpan">csv.stringify.Stringifier.prototype.</span>write (chunk, encoding, callback)](#apidoc.element.csv.stringify.Stringifier.prototype.write)
- description and source-code
```javascript
write = function (chunk, encoding, callback) {
  var base, e, error, preserve;
  if (chunk == null) {
    return;
  }
  preserve = typeof chunk !== 'object';
  if (!preserve) {
    if (this.countWriten === 0 && !Array.isArray(chunk)) {
      if ((base = this.options).columns == null) {
        base.columns = Object.keys(chunk);
      }
    }
    try {
      this.emit('record', chunk, this.countWriten);
    } catch (error) {
      e = error;
      return this.emit('error', e);
    }
    if (this.options.eof) {
      chunk = this.stringify(chunk) + this.options.rowDelimiter;
    } else {
      chunk = this.stringify(chunk);
      if (this.options.header || this.countWriten) {
        chunk = this.options.rowDelimiter + chunk;
      }
    }
  }
  if (typeof chunk === 'number') {
    chunk = "" + chunk;
  }
  if (this.countWriten === 0) {
    this.headers();
  }
  if (!preserve) {
    this.countWriten++;
  }
  return stream.Transform.prototype.write.call(this, chunk, encoding, callback);
}
```
- example usage
```shell
...

csv.generate({seed: 1, columns: 2, length: 20}, function(err, data){
  csv.parse(data, function(err, data){
    csv.transform(data, function(data){
      return data.map(function(value){return value.toUpperCase()});
    }, function(err, data){
      csv.stringify(data, function(err, data){
        process.stdout.write(data);
      });
    });
  });
});
'''

### Stream example
...
```



# <a name="apidoc.module.csv.transform"></a>[module csv.transform](#apidoc.module.csv.transform)

#### <a name="apidoc.element.csv.transform.transform"></a>[function <span class="apidocSignatureSpan">csv.</span>transform ()](#apidoc.element.csv.transform.transform)
- description and source-code
```javascript
transform = function () {
  var argument, callback, data, error, handler, i, j, k, len, options, result, transform, type, v;
  options = {};
  for (i = j = 0, len = arguments.length; j < len; i = ++j) {
    argument = arguments[i];
    type = typeof argument;
    if (argument === null) {
      type = 'null';
    } else if (type === 'object' && Array.isArray(argument)) {
      type = 'array';
    }
    if (i === 0) {
      if (type === 'function') {
        handler = argument;
      } else if (type !== null) {
        data = argument;
      }
      continue;
    }
    if (type === 'object') {
      for (k in argument) {
        v = argument[k];
        options[k] = v;
      }
    } else if (type === 'function') {
      if (handler && i === arguments.length - 1) {
        callback = argument;
      } else {
        handler = argument;
      }
    } else if (type !== 'null') {
      throw new Error('Invalid arguments');
    }
  }
  transform = new Transformer(options, handler);
  error = false;
  if (data) {
    process.nextTick(function() {
      var len1, m, row;
      for (m = 0, len1 = data.length; m < len1; m++) {
        row = data[m];
        if (error) {
          break;
        }
        transform.write(row);
      }
      return transform.end();
    });
  }
  if (callback || options.consume) {
    result = [];
    transform.on('readable', function() {
      var r, results;
      results = [];
      while ((r = transform.read())) {
        if (callback) {
          results.push(result.push(r));
        } else {
          results.push(void 0);
        }
      }
      return results;
    });
    transform.on('error', function(err) {
      error = true;
      if (callback) {
        return callback(err);
      }
    });
    transform.on('end', function() {
      if (callback && !error) {
        return callback(null, result);
      }
    });
  }
  return transform;
}
```
- example usage
```shell
...
Execute this script with the command 'node samples/callback.js'.

'''javascript
var csv = require('csv');

csv.generate({seed: 1, columns: 2, length: 20}, function(err, data){
csv.parse(data, function(err, data){
  csv.transform(data, function(data){
    return data.map(function(value){return value.toUpperCase()});
  }, function(err, data){
    csv.stringify(data, function(err, data){
      process.stdout.write(data);
    });
  });
});
...
```

#### <a name="apidoc.element.csv.transform.Transformer"></a>[function <span class="apidocSignatureSpan">csv.transform.</span>Transformer (options1, transform1)](#apidoc.element.csv.transform.Transformer)
- description and source-code
```javascript
Transformer = function (options1, transform1) {
  var base;
  this.options = options1 != null ? options1 : {};
  this.transform = transform1;
  this.options.objectMode = true;
  if ((base = this.options).parallel == null) {
    base.parallel = 100;
  }
  stream.Transform.call(this, this.options);
  this.running = 0;
  this.started = 0;
  this.finished = 0;
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.csv.transform.Transformer"></a>[module csv.transform.Transformer](#apidoc.module.csv.transform.Transformer)

#### <a name="apidoc.element.csv.transform.Transformer.Transformer"></a>[function <span class="apidocSignatureSpan">csv.transform.</span>Transformer (options1, transform1)](#apidoc.element.csv.transform.Transformer.Transformer)
- description and source-code
```javascript
Transformer = function (options1, transform1) {
  var base;
  this.options = options1 != null ? options1 : {};
  this.transform = transform1;
  this.options.objectMode = true;
  if ((base = this.options).parallel == null) {
    base.parallel = 100;
  }
  stream.Transform.call(this, this.options);
  this.running = 0;
  this.started = 0;
  this.finished = 0;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.transform.Transformer.super_"></a>[function <span class="apidocSignatureSpan">csv.transform.Transformer.</span>super_ (options)](#apidoc.element.csv.transform.Transformer.super_)
- description and source-code
```javascript
function Transform(options) {
  if (!(this instanceof Transform))
    return new Transform(options);

  Duplex.call(this, options);

  this._transformState = new TransformState(this);

  var stream = this;

  // start out asking for a readable event once data is transformed.
  this._readableState.needReadable = true;

  // we have implemented the _read method, and done the other things
  // that Readable wants before the first _read call, so unset the
  // sync guard flag.
  this._readableState.sync = false;

  if (options) {
    if (typeof options.transform === 'function')
      this._transform = options.transform;

    if (typeof options.flush === 'function')
      this._flush = options.flush;
  }

  // When the writable side finishes, then flush out anything remaining.
  this.once('prefinish', function() {
    if (typeof this._flush === 'function')
      this._flush(function(er) {
        done(stream, er);
      });
    else
      done(stream);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.csv.transform.Transformer.prototype"></a>[module csv.transform.Transformer.prototype](#apidoc.module.csv.transform.Transformer.prototype)

#### <a name="apidoc.element.csv.transform.Transformer.prototype._done"></a>[function <span class="apidocSignatureSpan">csv.transform.Transformer.prototype.</span>_done (err, chunks, cb)](#apidoc.element.csv.transform.Transformer.prototype._done)
- description and source-code
```javascript
_done = function (err, chunks, cb) {
  var chunk, j, len;
  this.running--;
  if (err) {
    return this.emit('error', err);
  }
  this.finished++;
  for (j = 0, len = chunks.length; j < len; j++) {
    chunk = chunks[j];
    if (typeof chunk === 'number') {
      chunk = "" + chunk;
    }
    if (chunk != null) {
      this.push(chunk);
    }
  }
  if (cb) {
    cb();
  }
  if (this._ending) {
    return this._ending();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.transform.Transformer.prototype._flush"></a>[function <span class="apidocSignatureSpan">csv.transform.Transformer.prototype.</span>_flush (cb)](#apidoc.element.csv.transform.Transformer.prototype._flush)
- description and source-code
```javascript
_flush = function (cb) {
  this._ending = function() {
    if (this.running === 0) {
      return cb();
    }
  };
  return this._ending();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv.transform.Transformer.prototype._transform"></a>[function <span class="apidocSignatureSpan">csv.transform.Transformer.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.csv.transform.Transformer.prototype._transform)
- description and source-code
```javascript
_transform = function (chunk, encoding, cb) {
  var callback, err, l;
  this.started++;
  this.running++;
  if (this.running < this.options.parallel) {
    cb();
    cb = null;
  }
  try {
    l = this.transform.length;
    if (this.options.params != null) {
      l--;
    }
    if (l === 1) {
      this._done(null, [this.transform.call(null, chunk, this.options.params)], cb);
    } else if (l === 2) {
      callback = (function(_this) {
        return function() {
          var chunks, err;
          err = arguments[0], chunks = 2 <= arguments.length ? slice.call(arguments, 1) : [];
          return _this._done(err, chunks, cb);
        };
      })(this);
      this.transform.call(null, chunk, callback, this.options.params);
    } else {
      throw Error("Invalid handler arguments");
    }
    return false;
  } catch (_error) {
    err = _error;
    return this._done(err);
  }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

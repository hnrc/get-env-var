# get-env-var

A little function that reads an environment variable from
`process.env` with support for default values.

It will thrown an exception if key key can't be found and no default
value is supplied.

[![build status](https://travis-ci.org/voldern/get-env-var.svg)](https://travis-ci.org/voldern/get-env-var)
[![modules status](https://david-dm.org/voldern/get-env-var.svg)](https://david-dm.org/voldern/get-env-var)

[![npm badge](https://nodei.co/npm/get-env-var.png?downloads=true)](https://nodei.co/npm/get-env-var)

# Example

```javascript
var getEnvVar = require('get-env-var');

var value = getEnvVar('foobar', 'defaultValue');
```

# License

MIT
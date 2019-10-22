### insight.is
---
https://insight.is/

https://github.com/bitpay/insight/


```js
// bitcore-node/service.js

var util = require('util');

util.inherits(Service, EventEmitter);

Service.dependencies = [];

Service.prototype.blockHandler = function(block, add, callback) {
  setImmediate(function() {
    callback(null, []);
  });
};
```

```
```


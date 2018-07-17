# @cush/execall v1.0.0

Returns a new array of `RegExp.prototype.exec` matches.

Forked from https://github.com/eush77/regexp.execall

```js
const all = require('@cush/execall');

all(regexp, string); // => []
```

- Empty matches are excluded from the array.
- When `regexp.global` is false, the array will either have one match or none.
- When `string` is falsy, the array will always be empty.

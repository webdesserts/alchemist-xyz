XYZ
---

The official RGB color-space plugin for alchemist.js.

XYZ acts as the center of all Alchemist.js color-spaces. XYZ does not know about or understand any other color-spaces and is essentially nothing but a value store. To drive that point home, here is the XYZ plugin in it's entirety:

```js
{
  name: 'xyz',
  to: {}
}
```

Usage
-----

### Node

By default alchemist-rgb is included in alchemist-common and consequently also
included in the bundled version of alchemist.js.

```js
  var alchemist = require('alchemist-js')
  alchemist.use(alchemist.common())
  var color = alchemize.rgb(255,255,255)
```

If you are not using alchemist.common you can instead use this library directly

```js
  var alchemist = require('alchemist-js')
  var rgb = require('alchemist-rgb')
  alchemist.use(rgb)
```

### Web

[coming soon]

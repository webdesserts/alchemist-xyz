XYZ
---

`alchemist-xyz` is the official **XYZ** color-space plugin for alchemist.js. It is
available as an [npm package][] and a [UMD module][]. It also is inlcuded by
default in [alchemist-common][] and consiquentially, alchemist itself.

[npm package]: https://www.npmjs.com/package/alchemist-xyz
[UMD Module]: /dist/
[alchemist-common]: https://www.npmjs.com/package/alchemist-common

XYZ acts as the center of all Alchemist.js color-spaces. XYZ does not know about
or understand any other color-spaces and is essentially nothing but a value
store. To drive that point home, here is the XYZ plugin in it's entirety:

```js
{
  name: 'xyz',
  to: {}
}
```

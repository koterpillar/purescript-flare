## Flare

Flare is a special-purpose UI library for
[Purescript](https://github.com/purescript/purescript). It is built on top
of [purescript-signal](https://github.com/bodil/purescript-signal) and uses
Applicative-style programming to combine predefined input fields to a reactive
user interface. Flare is inspired by the Haskell library
[typed-spreadsheet](https://github.com/Gabriel439/Haskell-Typed-Spreadsheet-Library).
The main design-criterion of this library is ease of use.

- [Introduction and tutorial with examples](http://david-peter.de/articles/flare/)
- [Tests with many additional examples](http://sharkdp.github.io/purescript-flare/)
- [Quick start project](https://github.com/sharkdp/flare-example)
- [Module documentation](http://pursuit.purescript.org/packages/purescript-flare/)

## Building
```
bower install
pulp build -O -I test -m Test.Main -t html/main.js
```

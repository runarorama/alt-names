# Alternate names for stuff in the Unison base libraries

This small library provides alternate names for things in the [Unison base libraries](https://github.com/unisonweb/base). For example:

* `Optional` aliased to `Option` and `Maybe`
* `Optional.Some` aliased to `Maybe.Just`
* `Optional.None` aliased to `Maybe.Nothing`
* `(.)` aliased to `compose`
* `curry` and `uncurry` aliased to `schönfinkel` and `unschönfinkel`, respectively

## Installation instructions

From `ucm`, the Unison Codebase Manager:

```
.> pull https://github.com/runarorama/unison-names .lib.names
```

Substitute for `.lib.names` whatever namespace where you want this to live in your codebase.

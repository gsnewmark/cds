---
title: "core.typed User Documentation Home"
layout: article
---

core.typed is an optional type system for Clojure.

## Quickstart

`(clojure.core.typed/ann v t)` gives var `v` the static type `t`.

`(clojure.core.typed/ann-form f t)` ensures form `f` is of the static type `t`.

`(clojure.core.typed/check-ns)` type checks the current namespace.

`(clojure.core.typed/cf t)` type checks the form `t`.

See the [Quick Guide](quick_guide.html).

## [Rationale](rationale.html)

Why core.typed exists, what can it do for you?

## Getting Started Guide

If you are new to core.typed, gradual type systems, or even types in general, and want to learn how
core.typed can help verify your programs, start here.

### [Introduction and Motivation](start/introduction_and_motivation.html)

We discuss some theory and design goals of core.typed.

### [Annotations](start/annotations.html)

Where and how to annotate your code to help core.typed.

### [Types](types.html)

Syntax and descriptions of core.typed types.

### [Filters](filters.html)

An overview of filters for occurrence typing.

### [Datatypes and Protocols](mm_protocol_datatypes.html)

Typing definitions and usages of Clojure datatypes and protocols.

### Multimethods

### Dotted Functions
### Polymorphism, Variance and F-Bounds
### Java Classes, Arrays and Interop

## Miscellaneous Tutorials

### [Hole-Driven Development](https://github.com/clojure/core.typed/blob/master/src/test/clojure/clojure/core/typed/test/hole.clj)

A fun diversion playing with holes.
- Requires some knowledge of Haskell.

## Examples

### [IRC Bot](https://github.com/frenchy64/Parjer)

## [Limitations](limitations.html) - Known issues

## Documentation Contributors

Ambrose Bonnaire-Sergeant (@ambrosebs)

Copyright 2013, Ambrose Bonnaire-Sergeant

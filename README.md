# Note

This repository is deprecated and no longer maintained. A comprehensive elliptic curve implementation for OCaml is the [mirage-crypto-ec](https://github.com/mirage/mirage-crypto) package (using [fiat](https://github.com/mit-plv/fiat-crypto), please use that instead.

If interested in [hacl-star](https://github.com/project-everest/hacl-star), use the official OCaml bindings.

[![Build Status](https://travis-ci.org/mirage/hacl.svg?branch=master)](https://travis-ci.org/mirage/hacl)

hacl
----

These are bindings to the various primitives present in [Project Everest].

In particular, the C code comes from this [snapshot] (from the hacl-star-raw 0.2.1 opam package, execute `./build_local.sh`). `Hacl_Hash.{c,h}` have been stripped down to only SHA-512.

[Project Everest]: https://project-everest.github.io/
[snapshot]: https://github.com/project-everest/hacl-star/commit/aabf2223a160b839f0380b0a2878e887ad4a5409

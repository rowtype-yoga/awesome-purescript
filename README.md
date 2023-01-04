# purescript-libraries

## Essential tools
- purs: the compiler
- spago: package manager and build tool
- esbuild: Javascript bundler used by spago

## Essential libraries
- prelude
- effect: for handling native side effects (equivalent to IO in Haskell)
- aff: asynchronous effects
- maybe
- either
- arrays: javascript arrays
- lists: linked lists
- transformers: monad transnformers ReaderT, StateT, MaybeT, etc (equivalent to mtl in Haskell)
- exists: encoding existential types.

## Data structures
- [sequences](https://github.com/hdgarrood/purescript-sequences)
- [tree-rose](https://github.com/JordanMartinez/purescript-tree-rose): tree zippers

## Maths
- [bigints](https://github.com/purescript-contrib/purescript-bigints): arbitrary length integers. This is a simple wrapper around biginteger.js
- [js-bigints](https://github.com/rowtype-yoga/purescript-js-bigints): alternative to bigints. FFI bindings for JavaScript's BigInt. Does not require external js libraries.
- [rationals](https://github.com/purescript-contrib/purescript-rationals): rational numbers
- vectors: 2d and 3d vectors
- fast-vect: vectors with size encoded in the type

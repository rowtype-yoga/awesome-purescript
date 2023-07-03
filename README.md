# Awesome Purescript《ミ》[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A collection of awesome Purescript libraries, resources and shiny things.

## Contents
- [Essential tools](#essential-tools)
- [Essential libraries](#essential-libraries)
- [Data types](#data-types)
- [Maths](#maths)
- [Random](#random)
- [Lenses](#lenses)
- [Http](#http)
    - [Http client](#http-client)
    - [Http server](#http-server)
    - [Http routing](#http-routing)
- [GraphQL](#graphql)
- [Json](#json)
- [UI](#ui)
    - [Halogen](#halogen)
    - [React](#react)
    - [Deku](#deku)
- [Web](#web)
- [CSS](#css)
- [Collaborative editing](#collaborative-editing)
- [Databases](#databases)
- [Testing](#testing)
- [Benchmark](#benchmark)
- [FFI](#ffi)
- [IDEs](#ides)
- [Organisations](#organisations)

## Essential tools
- purs - the compiler.
- spago - package manager and build tool.
- esbuild - JavaScript bundler used by spago.
- [purescript-backend-optimizer](https://github.com/aristanetworks/purescript-backend-optimizer) - A tool to optimize JS genererated code.

## Essential libraries
- [prelude](https://github.com/purescript/purescript-prelude) - The basic prelude.
- [effect](https://github.com/purescript/purescript-effect) - Native side effects (equivalent to IO in Haskell).
- [aff](https://github.com/purescript-contrib/purescript-aff) - Asynchronous effects.
- [maybe](https://github.com/purescript/purescript-maybe) - Optional values.
- [either](https://github.com/purescript/purescript-either) - Commonly used for error handling.
- [arrays](https://github.com/purescript/purescript-arrays) - JavaScript arrays.
- [transformers](https://github.com/purescript/purescript-transformers) - Monad transnformers ReaderT, StateT, MaybeT, etc (equivalent to mtl in Haskell).
- [exists](https://github.com/purescript/purescript-exists) - Encodes existential types.

## Data types
- [ordered-collections](https://github.com/purescript/purescript-ordered-collections) - Ordered Maps and Sets.
- [unordered-collections](https://github.com/fehrenbach/purescript-unordered-collections) - Hash-based immutable Maps and Sets.
- [lists](https://github.com/purescript/purescript-lists) - Linked lists.
- [fast-vect](https://github.com/sigma-andex/purescript-fast-vect) - Fast, type-safe vector libary for Purescript inspired by Idris. A vector is list with its size encoded in the type.
- [tree-rose](https://github.com/JordanMartinez/purescript-tree-rose) - Tree zippers.
- 📀 [record-studio](https://github.com/rowtype-yoga/purescript-record-studio) - Working with records made easy.
- 🎄 [yoga-tree](https://github.com/rowtype-yoga/purescript-yoga-tree) - A data type for representing trees with arbitrary number of children and handy zippers.
- 🕉️ [yoga-om](https://github.com/rowtype-yoga/purescript-yoga-om) - A powerful general purpose type for writing applications. Includes dependency injection via `Reader`, error `Variant`s and of course `Aff`.
- 💍 [untagged-union](https://github.com/rowtype-yoga/purescript-untagged-union) - A data type for untagged unions.
- 🔑 [vault](https://github.com/rowtype-yoga/purescript-vault) - A typed, persistent store for values of arbitrary types. This is a port of the Haskell [Vault](https://github.com/HeinrichApfelmus/vault) library by Heinrich Apfelmus.
- ❄️ [unique](https://github.com/rowtype-yoga/purescript-unique) - Abstract unique objects.

## Maths
- [js-bigints](https://github.com/rowtype-yoga/purescript-js-bigints) -  FFI bindings for JavaScript's BigInt. Does not require external js libraries.
- [rationals](https://github.com/purescript-contrib/purescript-rationals) - Rational numbers.

## Random
- [random](https://github.com/purescript/purescript-random) - A basic library to generate random numbers.
- [gen](https://github.com/purescript/purescript-gen) - A type class for random generator implementations.
- [generate-values](https://github.com/jordanmartinez/purescript-generate-values) - An instance for gen and additional functions.

## Lenses
- [profunctor-lenses](https://github.com/purescript-contrib/purescript-profunctor-lenses) - A mechanism for updating, viewing, and setting values within nested data structures.
- [barlow-lens](https://github.com/sigma-andex/purescript-barlow-lens) - Barlow lens makes creating complex lenses such as record lenses super simple.
- [tidy-codegen-lens](https://github.com/JordanMartinez/purescript-tidy-codegen-lens) - Generate lenses and prisms for your data types automatically. 

## Http

### Http client
- [fetch](https://github.com/rowtype-yoga/purescript-fetch) - High-level library for the WHATWG Fetch Living Standard.

### Http server
- [httpurple](https://github.com/sigma-andex/purescript-httpurple) - A functional http server with a focus on type-safety and making the common case easy.

### Http routing
- [routing-duplex](https://github.com/natefaubion/purescript-routing-duplex) - Simple bidirectional parser/printers for your routing data types.

## GraphQL
- [graphql-fundeps](https://github.com/rowtype-yoga/purescript-graphql-fundeps) - GraphQL client.

## Json
- [yoga-json](https://github.com/rowtype-yoga/purescript-yoga-json) - Light-weight Json parser.
- [argonaut](https://github.com/purescript-contrib/purescript-argonaut) - A collection of libraries for working with JSON in PureScript.
- [json-codecs](https://github.com/jordanmartinez/purescript-json-codecs) - A bidirectional and unidirectional value-based and runtime-configurable typeclass-based JSON codec library. 

## UI
### Halogen
- [halogen](https://github.com/purescript-halogen/purescript-halogen) - A declarative, component-based library entirely written in purescript.

### React
- [react-basic](https://github.com/purescript-react/purescript-react-basic) - A binding to the React library.
- [react-basic-hooks](https://github.com/purescript-react/purescript-react-basic-hooks) - React hook API for react-basic.
- [react-icons](https://github.com/purescript-react/purescript-react-icons) - [react-icons`](https://react-icons.github.io/react-icons/), a gigantic collection of high-quality icons, for Purescript.
- [nextjs](https://github.com/purescript-react/purescript-nextjs) - Use the #1 react framework in Purescript.

### Deku
- [deku](https://github.com/mikesol/purescript-deku) - A FRP web framework for apps that need to be fast. Have a nice documentation.

## Web
- [web-storage](https://github.com/purescript-web/purescript-web-storage) - A low-level library for local storage.
- [web-socket](https://github.com/purescript-web/purescript-web-socket) - A low-level library for web sockets.
- [web-workers](https://github.com/gbagan/purescript-web-workers) - A low-level library for web workers.

## CSS
- [tecton](https://github.com/nsaunders/purescript-tecton) - Domain-specific language for authoring CSS.

## Collaborative editing
- ⊗ [yjs](https://github.com/rowtype-yoga/purescript-yjs) - Purescript FFI bindings for [`yjs`](https://docs.yjs.dev).
- 🚰 [tiptap](https://github.com/rowtype-yoga/purescript-tiptap) - Purescript FFI bindings for [tiptap](https://tiptap.dev/).

## Databases
- 💾 [yoga-postgres](https://github.com/rowtype-yoga/purescript-yoga-postgres) - `node-postgres` FFI bindings, originally forked from [`purescript-node-postgres`](https://github.com/epost/purescript-node-postgres).
- 🦸🏻‍♂️ [supabase](https://github.com/rowtype-yoga/purescript-supabase) - Purescript FFI bindings for [`supabase`](https://supabase.com/).

## Testing
- [spec](https://github.com/purescript-spec/purescript-spec) - A testing framework, inspired by hspec.
- [quickcheck](https://github.com/purescript/purescript-quickcheck) - An implementation of QuickCheck in PureScript.
- [assert](https://github.com/purescript/purescript-assert) - Basic assertions library for low level testing.

## Benchmark
- [minibench](https://github.com/purescript/purescript-minibench) - A minimal benchmarking library.

## FFI
- 🦥 [lazy-joe](https://github.com/rowtype-yoga/purescript-lazy-joe) - Purescript ffi for the lazy joe.
- [js-objects](https://github.com/purescript-codegen/purescript-js-object) - Access js object methods and properties without writing JS bindings.

## IDEs
- [VS Code](https://github.com/nwolverson/vscode-ide-purescript) - VS Code extension.
- [IntelliJ](https://github.com/intellij-purescript/intellij-purescript) - IntelliJ extension.

## Organisations
The following organisations are the best entry points when looking for libraries (many of the libraries in this list come from these orgs):
- [purescript](https://github.com/purescript) - Core libraries for purescript.
- [purescript-contrib](https://github.com/purescript-contrib) - Common libraries that complement the core libraries.
- [purescript-web](https://github.com/purescript-web) - Low-level bindings to common web specifications (standards).
- [purescript-node](https://github.com/purescript-node) - Common libraries that complement the core libraries.
- [rowtype-yoga](https://github.com/rowtype-yoga) - High quality, type-safe libraries from us 😎.
- [purescript-react](https://github.com/purescript-react) - Libraries to work with the react ecosystem.

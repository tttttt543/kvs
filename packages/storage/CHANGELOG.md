# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [2.1.3](https://github.com/azu/kvs/compare/v2.1.2...v2.1.3) (2022-09-25)


### Bug Fixes

* **storage:** version saving issue ([#32](https://github.com/azu/kvs/issues/32)) ([49a0839](https://github.com/azu/kvs/commit/49a0839cbc59ffcf94f9dc07d1d01e83d44a8e40))





## [2.1.1](https://github.com/azu/kvs/compare/v2.1.0...v2.1.1) (2022-03-03)

**Note:** Version bump only for package @kvs/storage





# [2.0.0](https://github.com/azu/kvs/compare/v1.2.0...v2.0.0) (2022-02-19)


### Bug Fixes

* **storage:** use name as namespace ([#21](https://github.com/azu/kvs/issues/21)) ([2a8d783](https://github.com/azu/kvs/commit/2a8d7831bed970c94ae4fdad84639f5f373a8b6b))


### BREAKING CHANGES

* **storage:** storage package sperate storags by `name` option

## Affected Packages

- `@kvs/env` in Node.js
  - 📝 Browser is not affected because it uses IndexedDB
- `@kvs/storage`
- `@kvs/localstorage`
- `@kvs/memorystorage`
- `@kvs/node-localstorage`
- `@kvs/storage-sync`





# [1.2.0](https://github.com/azu/kvs/compare/v1.1.0...v1.2.0) (2021-04-17)


### Features

* **types:** Use Key Remapping in Mapped Types. ([#17](https://github.com/azu/kvs/issues/17)) ([7c099be](https://github.com/azu/kvs/commit/7c099be4ae39adedba78d111574347395e024362))


### BREAKING CHANGES

* **types:** require TypeScript 4.1+

It aims to support to following schema:

```ts
const storage = kvs<{
    [index: string]: string;
}>;
```





# [1.1.0](https://github.com/azu/kvs/compare/v1.0.0...v1.1.0) (2020-10-29)


### Features

* **examples:** add basic example ([#14](https://github.com/azu/kvs/issues/14)) ([351215d](https://github.com/azu/kvs/commit/351215d6c04158201768036caaa6e792c72717ea))





# [1.0.0](https://github.com/azu/kvs/compare/v0.3.1...v1.0.0) (2020-08-22)

**Note:** Version bump only for package @kvs/storage





# [0.3.0](https://github.com/azu/kvs/compare/v0.2.1...v0.3.0) (2020-08-22)


### Features

* **storage-sync:** add storage-sync package ([#11](https://github.com/azu/kvs/issues/11)) ([5748776](https://github.com/azu/kvs/commit/574877624202660c0427cd050d30e807d7bbbd26))





## [0.2.1](https://github.com/azu/kvs/compare/v0.2.0...v0.2.1) (2020-08-22)

**Note:** Version bump only for package @kvs/storage





# [0.2.0](https://github.com/azu/kvs/compare/v0.1.0...v0.2.0) (2020-08-08)


### Features

* **@kvs/indexeddb:** migrate Schema Type ([ec143e2](https://github.com/azu/kvs/commit/ec143e27d174271f4ce45f657e1ae644ef01591c))
* **@kvs/localstorage:** migrate to Schema type ([0c84640](https://github.com/azu/kvs/commit/0c84640c1c1d28955c60ca83d8a01bdce936d9ef))
* **storage:** use Schema interface ([2560aae](https://github.com/azu/kvs/commit/2560aae28d642c8f2e8ee5920dc1cc15f7c8c3f6))





# 0.1.0 (2020-08-08)


### Bug Fixes

* add deps ([b72e91a](https://github.com/azu/kvs/commit/b72e91aaa2487d69d44200ef0a11cc0b5f8fb904))


### Features

* **@kvs/node-localstorage:** add node implementation ([5160012](https://github.com/azu/kvs/commit/516001286c96ac85cb54d55fbba62549d6d7eb0e))
* add `close()` to interface ([a269d1d](https://github.com/azu/kvs/commit/a269d1dda6ce63388771e6fa4d897a26f284b72c))

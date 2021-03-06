# Changelog

### [4.3.3](https://www.github.com/zakodium/react-ocl/compare/v4.3.2...v4.3.3) (2021-03-23)


### Bug Fixes

* use JS extension ([9771140](https://www.github.com/zakodium/react-ocl/commit/977114035d99c956ce3d2f3da0bd7bc6cb057485))

### [4.3.2](https://www.github.com/zakodium/react-ocl/compare/v4.3.1...v4.3.2) (2021-03-23)


### Bug Fixes

* add commonjs build for SSR ([955d249](https://www.github.com/zakodium/react-ocl/commit/955d24937813fdae047e1eb5f9e9a09ef92b352d))

### [4.3.1](https://github.com/zakodium/react-ocl/compare/v4.3.0...v4.3.1) (2021-02-26)


### Bug Fixes

* prevent SVG recalculation if not needed ([#6](https://github.com/zakodium/react-ocl/issues/6)) ([004d729](https://github.com/zakodium/react-ocl/commit/004d729501b2193b13df507cca99c0212d20ed29))

# [4.3.0](https://github.com/zakodium/react-ocl/compare/v4.2.1...v4.3.0) (2020-09-09)


### Features

* expose base components for rendering with custom OCL ([66e6ee4](https://github.com/zakodium/react-ocl/commit/66e6ee4a9333bf50b118c8b41a74972419e2c31b))



## [4.2.1](https://github.com/zakodium/react-ocl/compare/v4.2.0...v4.2.1) (2020-06-10)


### Bug Fixes

* add missing main package field ([36bdf80](https://github.com/zakodium/react-ocl/commit/36bdf80be14fc562420ba957de733d807d9f36d8))



# [4.2.0](https://github.com/zakodium/react-ocl/compare/v4.1.0...v4.2.0) (2020-05-10)


### Features

* prevent atom selection and send event object ([#5](https://github.com/zakodium/react-ocl/issues/5)) ([07498f4](https://github.com/zakodium/react-ocl/commit/07498f48ff99d1c0c0c8b837cf4296c4d60ffc67))



# [4.1.0](https://github.com/zakodium/react-ocl/compare/v4.0.4...v4.1.0) (2020-05-07)


### Features

* **SVG:** catch syntax errors and add support for custom error component ([4c13201](https://github.com/zakodium/react-ocl/commit/4c1320109378ec7406552f91b0b9393c8836b705))



## [4.0.4](https://github.com/zakodium/react-ocl/compare/v4.0.3...v4.0.4) (2020-05-07)


### Bug Fixes

*  click event  listener ([88fde99](https://github.com/zakodium/react-ocl/commit/88fde997136cf2cae6f83dba9e955f82f6240e69))



## [4.0.3](https://github.com/zakodium/react-ocl/compare/v4.0.2...v4.0.3) (2019-11-28)


### Bug Fixes

* correct atom and bond highlighting ([caf1278](https://github.com/zakodium/react-ocl/commit/caf127866ed6e0c9e91a5e09cf001484393ebe41))



## [4.0.2](https://github.com/zakodium/react-ocl/compare/v4.0.1...v4.0.2) (2019-05-05)


### Bug Fixes

* **types:** correct type of IdcodeSvgRenderer props ([218b3b8](https://github.com/zakodium/react-ocl/commit/218b3b8))



## [4.0.1](https://github.com/zakodium/react-ocl/compare/v4.0.0...v4.0.1) (2019-05-05)


### Bug Fixes

* **types:** export types for default import ([6a2bebe](https://github.com/zakodium/react-ocl/commit/6a2bebe))



# [4.0.0](https://github.com/zakodium/react-ocl/compare/v3.1.1...v4.0.0) (2019-05-05)


### chore

* update OCL to 7.0.0 ([d990ebe](https://github.com/zakodium/react-ocl/commit/d990ebe))


### Code Refactoring

* **StructureEditor:** change arguments passed to onChange ([42e2a76](https://github.com/zakodium/react-ocl/commit/42e2a76))


### BREAKING CHANGES

* **StructureEditor:** Arguments passed to the `onChange` callback of `StructureEditor` were change. It will now receive two arguments: a molfile V3 and a Molecule instance.
* Highlight ids are now numbers instead of strings.



## [3.1.1](https://github.com/zakodium/react-ocl/compare/v3.1.0...v3.1.1) (2019-03-28)


### Bug Fixes

* better structure editor with hooks ([c1278e4](https://github.com/zakodium/react-ocl/commit/c1278e4))



# [3.1.0](https://github.com/zakodium/react-ocl/compare/v3.0.2...v3.1.0) (2019-03-28)


### Features

* add support for bond highlighting ([a48732e](https://github.com/zakodium/react-ocl/commit/a48732e))
* **highlight:** add onAtomEnter and onAtomLeave ([e31d70d](https://github.com/zakodium/react-ocl/commit/e31d70d))
* add support for controlled highlight ([77a0c57](https://github.com/zakodium/react-ocl/commit/77a0c57))



## [3.0.2](https://github.com/zakodium/react-ocl/compare/v3.0.1...v3.0.2) (2019-03-22)



## [3.0.1](https://github.com/zakodium/react-ocl/compare/v3.0.0...v3.0.1) (2019-01-27)

### Bug Fixes

- molfile prop doesn't have to be required ([538e51f](https://github.com/zakodium/react-ocl/commit/538e51f))

# [3.0.0](https://github.com/zakodium/react-ocl/compare/v2.0.1...v3.0.0) (2019-01-27)

### Bug Fixes

- update OCL to v6 ([5a0cdd5](https://github.com/zakodium/react-ocl/commit/5a0cdd5))

### BREAKING CHANGES

- The openchemlib peer dependency is now 6.0.0.

## [2.0.1](https://github.com/zakodium/react-ocl/compare/v2.0.0...v2.0.1) (2019-01-27)

### Bug Fixes

- use .mjs to tell entrypoints are modules ([a468b8b](https://github.com/zakodium/react-ocl/commit/a468b8b))

# [2.0.0](https://github.com/zakodium/react-ocl/compare/v1.0.1...v2.0.0) (2019-01-25)

### Bug Fixes

- **editor:** allow to pass a custom id ([e9f6639](https://github.com/zakodium/react-ocl/commit/e9f6639))

### Features

- export three versions of the library and make OCL prop obsolete ([0cd6a68](https://github.com/zakodium/react-ocl/commit/0cd6a68))

<a name="1.0.1"></a>

## [1.0.1](https://github.com/zakodium/react-ocl/compare/v1.0.0...v1.0.1) (2018-09-01)

<a name="1.0.0"></a>

# [1.0.0](https://github.com/zakodium/react-ocl/compare/v0.1.1...v1.0.0) (2018-01-09)

<a name="0.1.1"></a>

## [0.1.1](https://github.com/neptunjs/react-ocl/compare/v0.1.0...v0.1.1) (2017-11-01)

<a name="0.1.0"></a>

# [0.1.0](https://github.com/neptunjs/react-ocl/compare/v0.0.5...v0.1.0) (2017-02-08)

### Bug Fixes

- don't fallback to empty coordinates ([695936f](https://github.com/neptunjs/react-ocl/commit/695936f))

### Features

- require OCL in the props ([8c671da](https://github.com/neptunjs/react-ocl/commit/8c671da))

<a name="0.0.5"></a>

## [0.0.5](https://github.com/neptunjs/react-ocl/compare/v0.0.4...v0.0.5) (2017-02-07)

<a name="0.0.4"></a>

## [0.0.4](https://github.com/neptunjs/react-ocl/compare/v0.0.3...v0.0.4) (2017-02-07)

<a name="0.0.3"></a>

## [0.0.3](https://github.com/neptunjs/react-ocl/compare/v0.0.2...v0.0.3) (2017-01-26)

<a name="0.0.2"></a>

## [0.0.2](https://github.com/neptunjs/react-ocl/compare/v0.0.1...v0.0.2) (2017-01-26)

<a name="0.0.1"></a>

## 0.0.1 (2017-01-26)

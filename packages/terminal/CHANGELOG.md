# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [13.0.0](https://github.com/serialport/node-serialport/compare/v12.0.0...v13.0.0) (2024-12-24)


### Bug Fixes

* linting ([#2966](https://github.com/serialport/node-serialport/issues/2966)) ([867d8d2](https://github.com/serialport/node-serialport/commit/867d8d2eeb2ec76573991813d66cc99a0575db1b))


### chore

* Upgrade to @serialport/bindings-cpp 13 ([#2963](https://github.com/serialport/node-serialport/issues/2963)) ([a4ea1fe](https://github.com/serialport/node-serialport/commit/a4ea1fe7ad73d45eae642634aa1e17fc640b1368))


### BREAKING CHANGES

* This upgrade brings node 20 as the lowest supported version - no other changes





# [12.0.0](https://github.com/serialport/node-serialport/compare/v11.0.1...v12.0.0) (2023-08-29)

### Bug Fixes

- **deps:** update dependency @serialport/bindings-cpp to v12 ([#2691](https://github.com/serialport/node-serialport/issues/2691)) ([8034a8f](https://github.com/serialport/node-serialport/commit/8034a8ff59d3b02ec9fc8f880a003f85a64ddff5))
- **deps:** update dependency commander to v11 ([#2692](https://github.com/serialport/node-serialport/issues/2692)) ([39fc12b](https://github.com/serialport/node-serialport/commit/39fc12b8e56a99b1d1583659bc0a4d36debc7709))
- **deps:** update dependency enquirer to v2.4.1 ([#2690](https://github.com/serialport/node-serialport/issues/2690)) ([025ab02](https://github.com/serialport/node-serialport/commit/025ab0236ee751a15962503bc1114063db0487ad))

## [11.0.1](https://github.com/serialport/node-serialport/compare/v11.0.0...v11.0.1) (2023-07-27)

### Bug Fixes

- **deps:** update dependency @serialport/bindings-cpp to v11.0.3 ([#2658](https://github.com/serialport/node-serialport/issues/2658)) ([8100318](https://github.com/serialport/node-serialport/commit/8100318d68d374f12ccc8d1a4127533a800d6aaa))
- **deps:** update dependency @serialport/bindings-cpp to v11.0.3 ([#2662](https://github.com/serialport/node-serialport/issues/2662)) ([091528b](https://github.com/serialport/node-serialport/commit/091528baf7a4beb751c5407db23c8378df05dcf4))
- **deps:** update dependency @serialport/bindings-cpp to v12 ([#2660](https://github.com/serialport/node-serialport/issues/2660)) ([bfd9bad](https://github.com/serialport/node-serialport/commit/bfd9bad2c30bc0147893544f8d652fb7ac2640cf))

### Reverts

- Revert "fix(deps): update dependency @serialport/bindings-cpp to v12" (#2664) ([bbbf516](https://github.com/serialport/node-serialport/commit/bbbf5163cf82ed881efd12ed516c6e55f1304765)), closes [#2664](https://github.com/serialport/node-serialport/issues/2664)

# [11.0.0](https://github.com/serialport/node-serialport/compare/v10.4.0...v11.0.0) (2023-04-29)

### Bug Fixes

- **deps:** update dependency commander to v9.2.0 ([#2486](https://github.com/serialport/node-serialport/issues/2486)) ([4a14c4d](https://github.com/serialport/node-serialport/commit/4a14c4d817403c603c86be3a76c22634660a1a35))

### chore

- upgrade packages and minimum node ([#2630](https://github.com/serialport/node-serialport/issues/2630)) ([daffa1a](https://github.com/serialport/node-serialport/commit/daffa1ae78895b3ed51db708219b312845bcd82b))

### Features

- upgrade serialport/bindings-cpp ([#2557](https://github.com/serialport/node-serialport/issues/2557)) ([cbb344d](https://github.com/serialport/node-serialport/commit/cbb344d1f75b52ee83fca7c7598f952f8db9c956))

### BREAKING CHANGES

- drop node 12

# [10.5.0](https://github.com/serialport/node-serialport/compare/v10.4.0...v10.5.0) (2022-11-17)

### Bug Fixes

- **deps:** update dependency commander to v9.2.0 ([#2486](https://github.com/serialport/node-serialport/issues/2486)) ([4a14c4d](https://github.com/serialport/node-serialport/commit/4a14c4d817403c603c86be3a76c22634660a1a35))

### Features

- upgrade serialport/bindings-cpp ([4c07c80](https://github.com/serialport/node-serialport/commit/4c07c8077fe90af85b9b9d555a7a2b200c3bbb78))

# [10.4.0](https://github.com/serialport/node-serialport/compare/v10.3.0...v10.4.0) (2022-03-04)

### Features

- upgrade serialport-cpp for windows rts-mode ([#2448](https://github.com/serialport/node-serialport/issues/2448)) ([9f34f85](https://github.com/serialport/node-serialport/commit/9f34f85fc8109357190ecf115ce3099dd2dd7a69))

# [10.3.0](https://github.com/serialport/node-serialport/compare/v10.2.2...v10.3.0) (2022-02-14)

### Features

- have terminal ask for baudRate ([#2423](https://github.com/serialport/node-serialport/issues/2423)) ([d795f20](https://github.com/serialport/node-serialport/commit/d795f205f9384cacf6bfc73712d5ddc897da2f2e))
- platform specific open options ([#2428](https://github.com/serialport/node-serialport/issues/2428)) ([b3bead4](https://github.com/serialport/node-serialport/commit/b3bead45844498a9071c2e2edbcc2baf995bece5))

## [10.2.2](https://github.com/serialport/node-serialport/compare/v10.2.1...v10.2.2) (2022-02-05)

### Bug Fixes

- stopbits definition and move binding-mock ([#2419](https://github.com/serialport/node-serialport/issues/2419)) ([63ec6bb](https://github.com/serialport/node-serialport/commit/63ec6bb7d6be312bcc8d0976c9780325c9898632))

## [10.2.1](https://github.com/serialport/node-serialport/compare/v10.2.0...v10.2.1) (2022-02-03)

**Note:** Version bump only for package @serialport/terminal

# [10.2.0](https://github.com/serialport/node-serialport/compare/v10.1.0...v10.2.0) (2022-02-03)

### Features

- Typescript everything ([#2406](https://github.com/serialport/node-serialport/issues/2406)) ([7ae6e51](https://github.com/serialport/node-serialport/commit/7ae6e51a84738da1999863a80f4ec8ce7acd953a))

# [10.1.0](https://github.com/serialport/node-serialport/compare/v10.0.2...v10.1.0) (2022-01-23)

### Bug Fixes

- lint ([d7e81a0](https://github.com/serialport/node-serialport/commit/d7e81a0f25fbed3b005759a5a67743f53ece0fb9))

### Features

- **terminal:** Add flow control mode ([#2361](https://github.com/serialport/node-serialport/issues/2361)) ([311527e](https://github.com/serialport/node-serialport/commit/311527e9c6059f2d06873d932b025b940c5cfda7))

## [10.0.2](https://github.com/serialport/node-serialport/compare/v10.0.1...v10.0.2) (2022-01-08)

**Note:** Version bump only for package @serialport/terminal

## [10.0.1](https://github.com/serialport/node-serialport/compare/v10.0.0...v10.0.1) (2021-12-25)

**Note:** Version bump only for package @serialport/terminal

# [10.0.0](https://github.com/serialport/node-serialport/compare/v9.2.8...v10.0.0) (2021-12-11)

### Features

- Node-API migration ([#2305](https://github.com/serialport/node-serialport/issues/2305)) ([2fe7d43](https://github.com/serialport/node-serialport/commit/2fe7d434ca087f95a09ed9a3274d8b5f24e09ab4))

### BREAKING CHANGES

- This release switches to NAPI which changes how many binaries are released and will potentially break your build system

## [9.2.8](https://github.com/serialport/node-serialport/compare/v9.2.7...v9.2.8) (2021-11-26)

**Note:** Version bump only for package @serialport/terminal

## [9.2.7](https://github.com/serialport/node-serialport/compare/v9.2.5...v9.2.7) (2021-11-18)

**Note:** Version bump only for package @serialport/terminal

## [9.2.6](https://github.com/serialport/node-serialport/compare/v9.2.5...v9.2.6) (2021-11-18)

**Note:** Version bump only for package @serialport/terminal

## [9.2.5](https://github.com/serialport/node-serialport/compare/v9.2.4...v9.2.5) (2021-10-31)

**Note:** Version bump only for package @serialport/terminal

## [9.2.4](https://github.com/serialport/node-serialport/compare/v9.2.3...v9.2.4) (2021-09-28)

**Note:** Version bump only for package @serialport/terminal

## [9.2.3](https://github.com/serialport/node-serialport/compare/v9.2.1...v9.2.3) (2021-09-24)

**Note:** Version bump only for package @serialport/terminal

## [9.2.2](https://github.com/serialport/node-serialport/compare/v9.2.1...v9.2.2) (2021-09-24)

**Note:** Version bump only for package @serialport/terminal

## [9.2.1](https://github.com/serialport/node-serialport/compare/v9.2.0...v9.2.1) (2021-09-03)

**Note:** Version bump only for package @serialport/terminal

# [9.2.0](https://github.com/serialport/node-serialport/compare/v9.1.0...v9.2.0) (2021-06-19)

### Features

- Pin version numbers for all monorepo packages ([#2275](https://github.com/serialport/node-serialport/issues/2275)) ([4fbb973](https://github.com/serialport/node-serialport/commit/4fbb973e9ea7de4dd00494b9293a428ac1c3a1e2))

# [9.1.0](https://github.com/serialport/node-serialport/compare/v9.0.8...v9.1.0) (2021-05-28)

**Note:** Version bump only for package @serialport/terminal

## [9.0.8](https://github.com/serialport/node-serialport/compare/v9.0.9...v9.0.8) (2021-05-24)

**Note:** Version bump only for package @serialport/terminal

## [9.0.7](https://github.com/serialport/node-serialport/compare/v9.0.6...v9.0.7) (2021-02-22)

**Note:** Version bump only for package @serialport/terminal

## [9.0.4](https://github.com/serialport/node-serialport/compare/v9.0.3...v9.0.4) (2020-12-17)

**Note:** Version bump only for package @serialport/terminal

## [9.0.3](https://github.com/serialport/node-serialport/compare/v9.0.2...v9.0.3) (2020-12-04)

**Note:** Version bump only for package @serialport/terminal

## [9.0.2](https://github.com/serialport/node-serialport/compare/v9.0.1...v9.0.2) (2020-10-16)

**Note:** Version bump only for package @serialport/terminal

## [9.0.1](https://github.com/serialport/node-serialport/compare/v9.0.0...v9.0.1) (2020-08-08)

**Note:** Version bump only for package @serialport/terminal

# [9.0.0](https://github.com/serialport/node-serialport/compare/v8.0.8...v9.0.0) (2020-05-10)

**Note:** Version bump only for package @serialport/terminal

## [8.0.8](https://github.com/serialport/node-serialport/compare/v8.0.7...v8.0.8) (2020-05-07)

**Note:** Version bump only for package @serialport/terminal

## [8.0.7](https://github.com/serialport/node-serialport/compare/v8.0.6...v8.0.7) (2020-01-30)

### Bug Fixes

- uncomment node shebang line in terminal package ([#2023](https://github.com/serialport/node-serialport/issues/2023)) ([2a59726](https://github.com/serialport/node-serialport/commit/2a5972684367083595cf75e489f1165d24844423))

## [8.0.6](https://github.com/serialport/node-serialport/compare/v8.0.5...v8.0.6) (2019-12-25)

**Note:** Version bump only for package @serialport/terminal

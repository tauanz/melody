## master

## 1.1.0

### Features

- `[melody-compiler]`, `[meldoy-loader]` added `melody-logger`
- `[melody-idom]` added experimental synchronous deep rendering
- Added `melody-plugin-load-functions`
- Added `melody-plugin-skip-if`

### Fixes

- Added transform-object-rest-spread plugin
- `[melody-compiler]` remove `path.parse` dependency
- Fixed typo in call date filter
- Skip over all empty elements

### Chore & Maintenance

- Fix ci with workflows and test on node 6 & 8
- `[melody-runtime]` fix filter tests

## 1.0.4

### Fixes

- `[melody-idom]` revert commit [fdeef10](https://github.com/trivago/melody/commit/fdeef107bede824260916d458f956d3ee77d04e2): bugfix/remove-event-handlers
- `[melody-jest-transform]` fixed peer dependencies

## 1.0.3

### Docs

- Added dependancy installation steps to `README`

### Tests

- `[melody-code-frame]` added unit tests
- `[melody-jest-transform]` added unit tests

### Fixes

- Fixed `README` image
- `[melody-idom]` remove event handlers
- Compiler benchmark
- `[melody-types]` added missing constant type
- `[melody-runtime]` jest test cases with UTC timezone
- `[melody-compiler]`, `[melody-parser]` fix not in operator
- `[melody-idom]` draggable attribute to allow 'false' as value

### Chore & Maintenance

- Added bundle size status on `travis`
- Added Community guidelines for github repository
- Added Coveralls

## 1.0.2

### Fixes

- `[melody-idom]` ignore string refs if server-side rendered

## 1.0.1

### Features

- Added package `neutrino-preset-melody`

### Chore & Maintenance

- Setup `travis`

## <=1.0.1

- See commit history for changes in previous versions of jest.

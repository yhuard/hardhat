# @nomicfoundation/hardhat-foundry

## 1.1.2

### Patch Changes

- a93e240: Use absolute rather than relative path when overriding sources configuration
- Updated dependencies [22bcbf5]
- Updated dependencies [2c533f0]
- Updated dependencies [3203639]
- Updated dependencies [5d7a604]
- Updated dependencies [3c6de8f]
- Updated dependencies [6447e80]
  - hardhat@2.23.0

## 1.1.1

### Patch Changes

- 8af824dfd: Bump hardhat-foundry's peer dependency on Hardhat

## 1.1.0

### Minor Changes

- 9cb4f845d: Revamped how remappings are handled. Now they are passed to Hardhat's compile task, which handles them during file resolution.

## 1.0.3

### Patch Changes

- 3bdc9d6bb: Fixed a bug related to remappings that use the node_modules directory

## 1.0.2

### Patch Changes

- c52470de5: Fixed a performance issue that was causing compilation to be much slower when `hardhat-foundry` was used

## 1.0.1

### Patch Changes

- af0f9c1d3: Fixed a bug in how the configured sources paths are compared (thanks @bingryan!)

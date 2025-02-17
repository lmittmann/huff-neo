<!-- Keep a Changelog guide -> https://keepachangelog.com -->

# Node cache changelog

## [Unreleased]

## [1.0.0] - 2025-01-09
- First stable release of `huff-neo`
- Compiler binary is now `hnc` instead of `huffc`
- Update all dependencies to the latest version
- Restructure to a modern crate structure
- Replace `ethers` with `alloy`
- Remove spinner animation [#4](https://github.com/cakevm/huff-neo/pull/4)
- Fix relative position error for [#6](https://github.com/cakevm/huff-neo/pull/6)
  - Currently, this still fails for nested imports
- Replace `tiny-keccak` with the alloy version
- Add error for duplicate labels in the same macro [#7](https://github.com/cakevm/huff-neo/pull/7)
- Fix recursive error for empty import e.g. `#include ""`
- Fix error for nested imports with reoccurring imports

## [0.0.4] - 2025-01-09
- Improve error handling

## [0.0.3] - 2025-01-09
- Initial release of `huff-neo`
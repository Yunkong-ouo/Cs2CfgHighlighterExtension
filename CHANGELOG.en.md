<div align="right">

[繁體中文](./CHANGELOG.md) | [简体中文](./CHANGELOG.zh-CN.md) | **English**

</div>

<h1>Changelog</h1>

# [1.5.4]
## Changed
- **Adjusted language-configuration**:
  - `.` no longer splits words

# [1.5.3]
## New Features
- **New Matching Added**:
  - `exec`

## Improvements
- **Optimized Matching Logic**:
  - `alias` matching

- **New Commands**:
  - `noclip`

# [1.5.2]
## Improvements
- **Optimized Matching Logic**:
  - Numeric matching
  - `alias` matching
  - `setinfo` matching

- **Documentation Updates**:
  - Updated README text

- **New Commands**:
  - `quickinv`

# [1.5.1]
- **New Commands**:
  - `ignoremsg`
- **Bug Fixes**:
  - Fixed an issue where `alias` could not recognize `%`.

# [1.5.0]
- **New Commands**:
  - `getpos_exact`
  - `getpos`
  - `setpos`
  - `setang`
  - `setpos_player`
  - `setpos_exact`
  - `setang_exact`
  - `play`

# [1.4.9]
- Fixed conflicts between comments and syntax highlighting in `cs2script`.

# [1.4.8]
- Fixed syntax highlighting issues in `cs2script` and added some new matching rules.

# [1.4.7]
- Fixed some bugs and improved performance.
- Added syntax highlighting for `cs2script`.

# [1.4.6]
- Added highlighting for some commands.

# [1.4.5]
- Fixed issues related to numbers:
  - Resolved double-quote conflict issues.
  - Fixed other conflicting problems.

# [1.4.4]
- **Added Hash Matching Modes**:
  - Support for SHA-224, SHA-3(224, 256, 384, 512), and MD6(256/512).
  - Extended support for CRC32, Adler-32, and GOST hash functions.
  - Improved compatibility for non-standard hash lengths.

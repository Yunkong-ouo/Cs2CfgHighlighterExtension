<div align="right">

[繁體中文](./CHANGELOG.md) | [简体中文](./CHANGELOG.zh-CN.md) | **English**

</div>

<h1>Changelog</h1>

# [1.5.5]
- Added various new commands, provided by a contributor

# [1.5.4]
- Adjusted **language-configuration** settings:
  - `.` no longer splits words

# [1.5.3]
- Added matching:
  - Matching support for new `exec` command
- Optimized matching logic:
  - Improved matching for `alias`
- Added commands:
  - `noclip`

# [1.5.2]
- Optimized matching logic:
  - Number matching improvements
  - `alias` matching improvements
  - `setinfo` matching improvements
- Updated README documentation
- Added commands:
  - `quickinv`

# [1.5.1]
- Added commands:
  - `ignoremsg`
- Fixed issue where alias could not recognize `%`

# [1.5.0]
- Added commands:
  - `getpos_exact`
  - `getpos`
  - `setpos`
  - `setang`
  - `setpos_player`
  - `setpos_exact`
  - `setang_exact`
  - `play`

# [1.4.9]
- Fixed conflicts between cs2script comments and syntax highlighting

# [1.4.8]
- Fixed cs2script highlighting issues and added some matching support

# [1.4.7]
- Fixed multiple bugs and improved performance
- Added cs2script syntax highlighting

# [1.4.6]
- Added multiple command highlighting rules

# [1.4.5]
- Fixed number-related issues:
  - Resolved double quote conflicts
  - Fixed other conflicts

# [1.4.4]
- Added hash matching modes:
  - Support for SHA-224, SHA-3 (224, 256, 384, 512), MD6 (256/512)
  - Extended support for CRC32, Adler-32, and GOST hashes
  - Improved compatibility with non-standard hash lengths

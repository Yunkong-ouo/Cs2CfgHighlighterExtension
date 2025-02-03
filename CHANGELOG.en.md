<div align="right">

[繁體中文](./CHANGELOG.md) | [简体中文](./CHANGELOG.zh-CN.md) | **English**

</div>

# Changelog

## [1.5.2]
- Optimized matching logic:
  - Numeric matching (numeric-literal)
  - Alias matching (alias)
  - Setinfo matching (setinfo-pattern)
- Updated README text
- Added command:
  - quickinv

## [1.5.1]  
- Added command:  
  - `ignoremsg`  
- Fixed an issue where alias could not recognize `%`

## [1.5.0]  
- Added commands:  
  - `getpos_exact`  
  - `getpos`  
  - `setpos`  
  - `setang`  
  - `setpos_player`  
  - `setpos_exact`  
  - `setang_exact`  
  - `play`

## [1.4.9]
- Fixed the conflict between comments and syntax highlighting in cs2script.

## [1.4.8]
- Fixed cs2script highlighting and added some matches.

## [1.4.7]
- Fixed some bugs and optimized performance.
- Added cs2script highlighting feature.

## [1.4.6]
- Added highlighting for some commands.

## [1.4.5]
- Fixed issues related to numbers:
  - Resolved double quotation mark conflicts.
  - Fixed other conflict issues.

## [1.4.4]
- Added hash matching mode:
  - Support for SHA-224, SHA-3 (224, 256, 384, 512), and MD6 (256/512).
  - Extended support for CRC32, Adler-32, and GOST hashes.
  - Enhanced compatibility with non-standard hash lengths.
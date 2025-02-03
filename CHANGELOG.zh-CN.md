<div align="right">

[繁體中文](./CHANGELOG.md) | **简体中文** | [English](./CHANGELOG.en.md)

</div>

# 更新日志

## [1.5.2]
- 优化匹配逻辑：
  - 数字匹配（numeric-literal）
  - alias 匹配（alias）
  - setinfo 匹配（setinfo-pattern）
- 更新 README 文本
- 新增指令：
  - quickinv

## [1.5.1]  
- 新增指令：  
  - `ignoremsg`  
- 修复了 alias 无法识别 `%` 的问题

## [1.5.0]  
- 新增指令：  
  - `getpos_exact`  
  - `getpos`  
  - `setpos`  
  - `setang`  
  - `setpos_player`  
  - `setpos_exact`  
  - `setang_exact`  
  - `play`

## [1.4.9]
- 修正了 cs2script 的注释和高亮冲突。

## [1.4.8]
- 修正了 cs2script 高亮并新增一些匹配。

## [1.4.7]
- 修复了一些 bug 并优化性能。
- 新增了 cs2script 高亮功能。

## [1.4.6]
- 新增一些指令高亮。

## [1.4.5]
- 修复与数字相关的问题：
  - 解决双引号冲突问题。
  - 修正其他冲突问题。

## [1.4.4]
- 新增哈希匹配模式：
  - 支持 SHA-224、SHA-3（224、256、384、512）、MD6（256/512）。
  - 扩展对 CRC32、Adler-32 和 GOST 哈希的支持。
  - 增强对非标准哈希长度的兼容性。
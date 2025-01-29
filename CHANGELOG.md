<div align="right">

**繁體中文** | [簡體中文](./CHANGELOG.zh-CN.md) | [English](./CHANGELOG.en.md)

</div>

# 更新日誌

## [1.5.1]  
- 新增指令：  
  - `ignoremsg`  
- 修復了 alias 無法識別 `%` 的問題

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
- 修正了 cs2script 的註解和高亮衝突。

## [1.4.8]
- 修正了 cs2script 高亮並新增一些匹配。

## [1.4.7]
- 修復了一些 bug 並優化效能。
- 新增了 cs2script 高亮功能。

## [1.4.6]
- 新增一些指令高亮。

## [1.4.5]
- 修復與數字相關的問題：
  - 解決雙引號衝突問題。
  - 修正其他衝突問題。

## [1.4.4]
- 新增哈希匹配模式：
  - 支援 SHA-224、SHA-3（224、256、384、512）、MD6（256/512）。
  - 擴展對 CRC32、Adler-32 和 GOST 哈希的支援。
  - 增強對非標準哈希長度的相容性。

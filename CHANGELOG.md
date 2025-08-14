<div align="right">

**繁體中文** | [簡體中文](./CHANGELOG.zh-CN.md) | [English](./CHANGELOG.en.md)

</div>

<h1>更新日誌</h1>

# [1.5.6]
- 修復與優化
  - 修復了 `exec` 沒正確匹配
  - 優化了匹配邏輯
  - 移除重複的匹配

# [1.5.5]
- 新增多種指令，由大佬提供

# [1.5.4]
- 調整 **language-configuration** 設定：
  - `.` 不再作為單詞分割符

# [1.5.3]
- 新增匹配：
  - 匹配支持新增 `exec` 指令
- 優化匹配邏輯：
  - 改善 `alias` 的匹配效果
- 新增指令：
  - `noclip`

# [1.5.2]
- 優化匹配邏輯：
  - 數字匹配優化
  - `alias` 匹配優化
  - `setinfo` 匹配優化
- 更新 README 文檔
- 新增指令：
  - `quickinv`

# [1.5.1]
- 新增指令：
  - `ignoremsg`
- 修復 alias 無法識別 `%` 的問題

# [1.5.0]
- 新增指令：
  - `getpos_exact`
  - `getpos`
  - `setpos`
  - `setang`
  - `setpos_player`
  - `setpos_exact`
  - `setang_exact`
  - `play`

# [1.4.9]
- 修正 cs2script 註解與語法高亮的衝突問題

# [1.4.8]
- 修正 cs2script 高亮問題並新增部分匹配支持

# [1.4.7]
- 修復多項 Bug，提升效能
- 新增 cs2script 語法高亮功能

# [1.4.6]
- 新增多條指令高亮規則

# [1.4.5]
- 修復與數字相關的問題：
  - 解決雙引號衝突
  - 修正其他衝突

# [1.4.4]
- 新增哈希匹配模式：
  - 支援 SHA-224、SHA-3（224、256、384、512）、MD6（256/512）
  - 擴展對 CRC32、Adler-32 及 GOST 哈希的支援
  - 增強對非標準哈希長度的兼容性

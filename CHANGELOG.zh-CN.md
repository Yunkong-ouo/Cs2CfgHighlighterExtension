<div align="right">

[繁體中文](./CHANGELOG.md) | **简体中文** | [English](./CHANGELOG.en.md)

</div>

<h1>更新日志</h1>

# [1.5.6]
- 修复与优化
  - 修复了 `exec` 没有正确匹配的问题
  - 优化了匹配逻辑
  - 移除重复的匹配

# [1.5.5]
- 新增多种指令，由大佬提供

# [1.5.4]
- 调整 **language-configuration** 设置：
  - `.` 不再作为单词分割符

# [1.5.3]
- 新增匹配：
  - 匹配支持新增 `exec` 指令
- 优化匹配逻辑：
  - 改善 `alias` 的匹配效果
- 新增指令：
  - `noclip`

# [1.5.2]
- 优化匹配逻辑：
  - 数字匹配优化
  - `alias` 匹配优化
  - `setinfo` 匹配优化
- 更新 README 文档
- 新增指令：
  - `quickinv`

# [1.5.1]
- 新增指令：
  - `ignoremsg`
- 修复 alias 无法识别 `%` 的问题

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
- 修正 cs2script 注释与语法高亮的冲突问题

# [1.4.8]
- 修正 cs2script 高亮问题并新增部分匹配支持

# [1.4.7]
- 修复多项 Bug，提升性能
- 新增 cs2script 语法高亮功能

# [1.4.6]
- 新增多条指令高亮规则

# [1.4.5]
- 修复与数字相关的问题：
  - 解决双引号冲突
  - 修正其他冲突

# [1.4.4]
- 新增哈希匹配模式：
  - 支持 SHA-224、SHA-3（224、256、384、512）、MD6（256/512）
  - 扩展对 CRC32、Adler-32 及 GOST 哈希的支持
  - 增强对非标准哈希长度的兼容性

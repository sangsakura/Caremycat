咕噜罐头管家 FINAL 4.2 安全导入版

只修复导入安全性，不改变FINAL 4.1页面结构与计划算法。

安全机制：
- iPhone使用FileReader读取TXT/JSON/无扩展名文件。
- 选择文件后仅显示导入预览，不立即覆盖。
- 预览显示库存件数、SKU、批次、摄入记录。
- 仅点击“确认导入并重算”后才替换。
- 任意错误自动恢复导入前内存状态和localStorage。
- 恢复内置数据必须输入完整确认短语。

支持FINAL 3/4、catCanTrackerV1、gulu-openplan-max2、activeCatId+pantry及顶层pantry数组。

GitHub：用ZIP内index.html覆盖仓库根目录旧index.html。
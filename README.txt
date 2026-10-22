咕噜罐头管家 FINAL 4.1

重点修复导入：先解析、转换、校验，全部成功后才覆盖当前数据；导入失败会自动回滚，不会出现空库存/空设置。
兼容 FINAL 3/4、catCanTrackerV1、gulu-openplan-max2、原APP activeCatId+pantry，以及顶层pantry数组。
导入成功后弹窗会显示导入库存件数和SKU数。
仍保留FINAL 4.0的硬规则：任何一天最多2个未吃完；现有余量足够不新开；每周2-3种只作为轮换目标；85g不优先；7/30天磷预算与GX覆盖率。
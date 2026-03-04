# 商品表（product）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | bigint | — | 是 | 是 | 商品ID |
| 2 | name | varchar | 100 | 是 | 否 | 商品名称 |
| 3 | category | varchar | 50 | 否 | 否 | 分类 |
| 4 | price | decimal | 10,2 | 是 | 否 | 价格 |
| 5 | stock | int | — | 是 | 否 | 库存 |
| 6 | description | text | — | 否 | 否 | 描述 |
| 7 | images | varchar | 500 | 否 | 否 | 图片 |
| 8 | status | tinyint | — | 否 | 否 | 状态(0:下架,1:上架) |
| 9 | create_time | datetime | — | 否 | 否 | 创建时间 |
| 10 | update_time | datetime | — | 否 | 否 | 更新时间 |

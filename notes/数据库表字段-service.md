# 服务表（service）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | bigint | — | 是 | 是 | 服务ID |
| 2 | name | varchar | 100 | 是 | 否 | 服务名称 |
| 3 | category_id | bigint | — | 否 | 否 | 分类ID |
| 4 | price | decimal | 10,2 | 是 | 否 | 价格 |
| 5 | description | text | — | 否 | 否 | 描述 |
| 6 | duration | int | — | 否 | 否 | 时长(分钟) |
| 7 | status | tinyint | — | 否 | 否 | 状态(0:停用,1:启用) |
| 8 | create_time | datetime | — | 否 | 否 | 创建时间 |
| 9 | update_time | datetime | — | 否 | 否 | 更新时间 |

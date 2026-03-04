# 购物车表（cart）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | bigint | — | 是 | 是 | 购物车项ID |
| 2 | user_id | bigint | — | 是 | 否 | 用户ID |
| 3 | product_id | bigint | — | 是 | 否 | 商品ID |
| 4 | quantity | int | — | 是 | 否 | 商品数量 |
| 5 | create_time | datetime | — | 否 | 否 | 创建时间 |
| 6 | update_time | datetime | — | 否 | 否 | 更新时间 |

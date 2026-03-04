# 订单评价表（order_review）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | bigint | — | 是 | 是 | 评价ID |
| 2 | order_id | bigint | — | 是 | 否 | 订单ID |
| 3 | user_id | bigint | — | 是 | 否 | 用户ID |
| 4 | product_id | bigint | — | 是 | 否 | 商品ID |
| 5 | rating | int | — | 是 | 否 | 评分(1-5星) |
| 6 | content | text | — | 是 | 否 | 评价内容 |
| 7 | images | text | — | 否 | 否 | 评价图片 |
| 8 | is_anonymous | tinyint | — | 是 | 否 | 是否匿名 |
| 9 | reply | text | — | 否 | 否 | 商家回复 |
| 10 | reply_time | datetime | — | 否 | 否 | 回复时间 |
| 11 | create_time | datetime | — | 是 | 否 | 创建时间 |
| 12 | update_time | datetime | — | 是 | 否 | 更新时间 |

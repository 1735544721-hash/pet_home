# 寄养信息表（boarding）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | bigint | — | 是 | 是 | 寄养ID |
| 2 | user_id | bigint | — | 是 | 否 | 用户ID |
| 3 | pet_name | varchar | 50 | 是 | 否 | 宠物名称 |
| 4 | pet_type | varchar | 50 | 否 | 否 | 宠物类型 |
| 5 | start_time | datetime | — | 是 | 否 | 开始时间 |
| 6 | end_time | datetime | — | 是 | 否 | 结束时间 |
| 7 | status | varchar | 20 | 是 | 否 | 状态(已申请/已接受/进行中/已完成/已取消) |
| 8 | requirements | text | — | 否 | 否 | 特殊要求 |
| 9 | price | decimal | 10,2 | 否 | 否 | 价格 |
| 10 | create_time | datetime | — | 否 | 否 | 创建时间 |
| 11 | update_time | datetime | — | 否 | 否 | 更新时间 |

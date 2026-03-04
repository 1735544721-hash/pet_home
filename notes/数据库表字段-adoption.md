# 领养申请表（adoption）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | bigint | — | 是 | 是 | 申请ID |
| 2 | user_id | bigint | — | 是 | 否 | 用户ID |
| 3 | pet_id | bigint | — | 是 | 否 | 宠物ID |
| 4 | status | varchar | 20 | 是 | 否 | 状态(已申请/审核中/已通过/已拒绝) |
| 5 | apply_reason | text | — | 否 | 否 | 申请理由 |
| 6 | contact_phone | varchar | 20 | 否 | 否 | 联系电话 |
| 7 | address | varchar | 200 | 否 | 否 | 地址 |
| 8 | create_time | datetime | — | 否 | 否 | 创建时间 |
| 9 | update_time | datetime | — | 否 | 否 | 更新时间 |

# 服务预约表（service_appointment）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | contact_phone | varchar | 255 | 否 | 否 | 联系电话 |
| 2 | id | bigint | — | 是 | 是 | 预约ID |
| 3 | user_id | bigint | — | 是 | 否 | 用户ID |
| 4 | service_id | bigint | — | 是 | 否 | 服务ID |
| 5 | appointment_time | datetime | — | 是 | 否 | 预约时间 |
| 6 | status | varchar | 20 | 是 | 否 | 状态(已预约/已确认/已完成/已取消) |
| 7 | pet_name | varchar | 50 | 是 | 否 | 宠物名称 |
| 8 | requirements | text | — | 否 | 否 | 特殊要求 |
| 9 | create_time | datetime | — | 否 | 否 | 创建时间 |
| 10 | update_time | datetime | — | 否 | 否 | 更新时间 |

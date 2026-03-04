# 训练预约表（training_appointment）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | contact_phone | varchar | 255 | 否 | 否 | 联系方式 |
| 2 | id | bigint | — | 是 | 是 | 预约ID |
| 3 | user_id | bigint | — | 是 | 否 | 用户ID |
| 4 | course_id | bigint | — | 是 | 否 | 课程ID |
| 5 | pet_name | varchar | 50 | 是 | 否 | 宠物名称 |
| 6 | appointment_time | datetime | — | 是 | 否 | 预约时间 |
| 7 | status | varchar | 20 | 是 | 否 | 状态(已预约/已确认/已完成/已取消) |
| 8 | requirements | text | — | 否 | 否 | 特殊要求 |
| 9 | progress | int | — | 否 | 否 | 进度(0-100) |
| 10 | create_time | datetime | — | 否 | 否 | 创建时间 |
| 11 | update_time | datetime | — | 否 | 否 | 更新时间 |
| 12 | rating | int | — | 否 | 否 | 满意度评分 |
| 13 | feedback | text | — | 否 | 否 | 反馈内容 |
| 14 | feedback_time | datetime | — | 否 | 否 | 反馈时间 |

# 系统公告表（sys_announcement）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | bigint | — | 是 | 是 | 公告ID |
| 2 | title | varchar | 100 | 是 | 否 | 公告标题 |
| 3 | content | text | — | 否 | 否 | 公告内容 |
| 4 | type | varchar | 20 | 否 | 否 | 公告类型 |
| 5 | status | tinyint | — | 否 | 否 | 状态(0:禁用,1:正常) |
| 6 | created_by | bigint | — | 否 | 否 | 创建人ID |
| 7 | created_time | datetime | — | 否 | 否 | 创建时间 |
| 8 | updated_time | datetime | — | 否 | 否 | 更新时间 |

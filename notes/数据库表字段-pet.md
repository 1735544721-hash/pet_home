# 宠物信息表（pet）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | bigint | — | 是 | 是 | 宠物ID |
| 2 | name | varchar | 50 | 是 | 否 | 宠物名称 |
| 3 | breed | varchar | 50 | 否 | 否 | 品种 |
| 4 | age | int | — | 否 | 否 | 年龄 |
| 5 | gender | varchar | 10 | 否 | 否 | 性别 |
| 6 | health_status | varchar | 200 | 否 | 否 | 健康状况 |
| 7 | description | text | — | 否 | 否 | 描述 |
| 8 | images | varchar | 500 | 否 | 否 | 图片 |
| 9 | adoption_status | varchar | 20 | 否 | 否 | 领养状态 |
| 10 | create_time | datetime | — | 否 | 否 | 创建时间 |
| 11 | update_time | datetime | — | 否 | 否 | 更新时间 |
| 12 | category_id | bigint | — | 否 | 否 | 宠物分类ID |

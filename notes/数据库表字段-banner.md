# 轮播图表（banner）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | bigint | — | 是 | 是 | 轮播图ID |
| 2 | title | varchar | 100 | 否 | 否 | 标题 |
| 3 | image_url | varchar | 200 | 是 | 否 | 图片URL |
| 4 | link_url | varchar | 200 | 否 | 否 | 链接URL |
| 5 | sort | int | — | 否 | 否 | 排序 |
| 6 | status | tinyint | — | 否 | 否 | 状态(0:禁用,1:正常) |
| 7 | create_time | datetime | — | 否 | 否 | 创建时间 |
| 8 | update_time | datetime | — | 否 | 否 | 更新时间 |

# 系统角色表（sys_role）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | int | — | 是 | 是 | 角色ID |
| 2 | code | varchar | 50 | 是 | 否 | 角色编码 |
| 3 | name | varchar | 50 | 是 | 否 | 角色名称 |
| 4 | description | varchar | 200 | 否 | 否 | 描述 |
| 5 | created_time | datetime | — | 否 | 否 | 创建时间 |
| 6 | updated_time | datetime | — | 否 | 否 | 更新时间 |

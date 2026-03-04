# 疫苗接种记录表（pet_vaccination）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | bigint | — | 是 | 是 | 接种ID |
| 2 | pet_id | bigint | — | 是 | 否 | 宠物ID |
| 3 | vaccine_name | varchar | 100 | 是 | 否 | 疫苗名称 |
| 4 | vaccination_date | datetime | — | 是 | 否 | 接种日期 |
| 5 | next_date | datetime | — | 否 | 否 | 下次接种日期 |
| 6 | hospital | varchar | 100 | 否 | 否 | 接种医院 |
| 7 | batch_number | varchar | 50 | 否 | 否 | 疫苗批号 |
| 8 | notes | text | — | 否 | 否 | 备注 |
| 9 | create_time | datetime | — | 否 | 否 | 创建时间 |
| 10 | update_time | datetime | — | 否 | 否 | 更新时间 |

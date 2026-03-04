# 宠物健康记录表（pet_health_record）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | bigint | — | 是 | 是 | 记录ID |
| 2 | pet_id | bigint | — | 是 | 否 | 宠物ID |
| 3 | user_id | bigint | — | 是 | 否 | 主人ID |
| 4 | record_type | varchar | 50 | 是 | 否 | 记录类型(体检/疫苗/就诊/手术) |
| 5 | record_date | datetime | — | 是 | 否 | 记录日期 |
| 6 | hospital | varchar | 100 | 否 | 否 | 医院名称 |
| 7 | doctor | varchar | 50 | 否 | 否 | 医生姓名 |
| 8 | weight | decimal | 5,2 | 否 | 否 | 体重(kg) |
| 9 | temperature | decimal | 3,1 | 否 | 否 | 体温(℃) |
| 10 | heart_rate | int | — | 否 | 否 | 心率(次/分) |
| 11 | blood_pressure | varchar | 20 | 否 | 否 | 血压 |
| 12 | respiratory_rate | int | — | 否 | 否 | 呼吸频率(次/分) |
| 13 | skin_condition | varchar | 200 | 否 | 否 | 皮肤状况 |
| 14 | fur_condition | varchar | 200 | 否 | 否 | 毛发状况 |
| 15 | eye_condition | varchar | 200 | 否 | 否 | 眼部状况 |
| 16 | ear_condition | varchar | 200 | 否 | 否 | 耳部状况 |
| 17 | oral_condition | varchar | 200 | 否 | 否 | 口腔状况 |
| 18 | limb_condition | varchar | 200 | 否 | 否 | 四肢状况 |
| 19 | diagnosis_results | text | — | 否 | 否 | 诊断和检查结果 |
| 20 | health_suggestions | text | — | 否 | 否 | 健康建议(包括饮食和活动) |
| 21 | notes | text | — | 否 | 否 | 备注 |
| 22 | create_time | datetime | — | 否 | 否 | 创建时间 |
| 23 | update_time | datetime | — | 否 | 否 | 更新时间 |

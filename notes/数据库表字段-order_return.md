# 订单退货表（order_return）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | bigint | — | 是 | 是 | 退货ID |
| 2 | order_id | bigint | — | 是 | 否 | 订单ID |
| 3 | user_id | bigint | — | 是 | 否 | 用户ID |
| 4 | reason | varchar | 500 | 是 | 否 | 退货原因 |
| 5 | status | varchar | 20 | 是 | 否 | 退货状态(待处理/已同意/已拒绝) |
| 6 | description | text | — | 否 | 否 | 问题描述 |
| 7 | images | text | — | 否 | 否 | 图片凭证 |
| 8 | refund_amount | decimal | 10,2 | 是 | 否 | 退款金额 |
| 9 | operator | varchar | 50 | 否 | 否 | 处理人 |
| 10 | operator_note | varchar | 500 | 否 | 否 | 处理备注 |
| 11 | create_time | datetime | — | 是 | 否 | 创建时间 |
| 12 | update_time | datetime | — | 是 | 否 | 更新时间 |
| 13 | previous_order_status | varchar | 20 | 否 | 否 | 申请退货前的订单状态 |
| 14 | process_time | datetime | — | 否 | 否 | 处理时间 |

# 发货信息表（shipping）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | id | bigint | — | 是 | 是 | 发货ID |
| 2 | order_id | bigint | — | 是 | 否 | 订单ID |
| 3 | order_no | varchar | 50 | 是 | 否 | 订单编号 |
| 4 | shipping_no | varchar | 50 | 是 | 否 | 发货单号 |
| 5 | delivery_company | varchar | 50 | 否 | 否 | 快递公司 |
| 6 | tracking_no | varchar | 50 | 否 | 否 | 快递单号 |
| 7 | delivery_time | datetime | — | 否 | 否 | 发货时间 |
| 8 | receipt_time | datetime | — | 否 | 否 | 收货时间 |
| 9 | shipping_status | varchar | 20 | 是 | 否 | 配送状态(待发货/已发货/已签收/已退回) |
| 10 | operator | varchar | 50 | 否 | 否 | 操作人 |
| 11 | notes | varchar | 200 | 否 | 否 | 备注 |
| 12 | create_time | datetime | — | 否 | 否 | 创建时间 |
| 13 | update_time | datetime | — | 否 | 否 | 更新时间 |

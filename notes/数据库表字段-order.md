# 订单表（order）字段清单

来源：`pet_home/宠物之家/pet_home.sql`

| 编号 | 字段名 | 类型 | 长度 | 是否非空 | 是否主键 | 注释 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | previous_order_status | varchar | 255 | 否 | 否 | 退货前状态 |
| 2 | id | bigint | — | 是 | 是 | 订单ID |
| 3 | user_id | bigint | — | 是 | 否 | 用户ID |
| 4 | order_no | varchar | 50 | 是 | 否 | 订单编号 |
| 5 | product_id | bigint | — | 是 | 否 | 商品ID |
| 6 | quantity | int | — | 是 | 否 | 商品数量 |
| 7 | price | decimal | 10,2 | 是 | 否 | 商品单价 |
| 8 | total_amount | decimal | 10,2 | 是 | 否 | 订单总金额 |
| 9 | payment_method | varchar | 20 | 否 | 否 | 支付方式 |
| 10 | payment_time | datetime | — | 否 | 否 | 支付时间 |
| 11 | status | varchar | 20 | 是 | 否 | 订单状态(待付款/待发货/待收货/已完成/已取消) |
| 12 | is_returned | tinyint | — | 是 | 否 | 是否已退货 |
| 13 | return_time | datetime | — | 否 | 否 | 退货时间 |
| 14 | is_reviewed | tinyint | — | 是 | 否 | 是否已评价 |
| 15 | review_time | datetime | — | 否 | 否 | 评价时间 |
| 16 | address | varchar | 200 | 是 | 否 | 收货地址 |
| 17 | contact_name | varchar | 50 | 是 | 否 | 联系人 |
| 18 | contact_phone | varchar | 20 | 是 | 否 | 联系电话 |
| 19 | remark | varchar | 200 | 否 | 否 | 订单备注 |
| 20 | create_time | datetime | — | 否 | 否 | 创建时间 |
| 21 | update_time | datetime | — | 否 | 否 | 更新时间 |
| 22 | payment_deadline | datetime | — | 否 | 否 | 支付截止时间 |

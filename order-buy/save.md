# 入参

* url：```https://2858y3h397.qicp.vip/cxwx/order/save```
* type:POST
* params:

| 字段        | 类型   | 是否必填 |
| ----------- | ------ | -------- |
| token       | string | 是       |
| temp        | string | 是       |
| phone       | string | 是       |
| contacts    | string | 是       |
| car         | string | 是       |
| entName     | string | 是       |
| totalWeight | string | 是       |
| totalPrice  | string | 是       |
| adress      | string | 是       |



# 出参

| 字段    | 类型    | 值                     |
| ------- | ------- | ---------------------- |
| status  | Integer | 1 成功<br />其他值失败 |
| message | String  | status的描述信息       |


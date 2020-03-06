# 入参

* url:```https://2858y3h397.qicp.vip/cxwx/order/orderEdit```
* type:GET
* params:

| 字段  | 类型   | 是否必填 |
| ----- | ------ | -------- |
| token | string | 是       |
| id    | string | 是       |



# 出参

| 字段    | 类型       | 值                                                           |
| ------- | ---------- | ------------------------------------------------------------ |
| status  | Integer    | 1 成功<br />其他值表示失败                                   |
| message | String     | status的描述信息                                             |
| data    | JsonObject | {<br />order:Order<br />carrList：`List<CarReceive>`<br />suList:`List<SupplierEnt>`} |


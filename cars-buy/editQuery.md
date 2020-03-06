# 入参

* url：```https://2858y3h397.qicp.vip/cxwx/carReceive/edit```
* type：GET
* params：

| 字段  | 类型   | 是否必填 |
| ----- | ------ | -------- |
| token | string | 是       |
| id    | string | 是       |



# 出参

| 字段    | 类型       | 值                                                           |
| ------- | ---------- | ------------------------------------------------------------ |
| status  | Integer    | 1 成功<br />其他值失败                                       |
| message | string     | status的描述                                                 |
| data    | JsonObject | {<br />dropList:`List<MineralDrop>`<br />bean:`CarReceive`<br />} |


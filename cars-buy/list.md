# 入参

* url：```https://2858y3h397.qicp.vip/cxwx/carReceive/listByPage```
* type:GET
* params:

| 字段       | 类型       | 是否必填 |
| ---------- | ---------- | -------- |
| token      | string     | 是       |
| bean       | CarReceive | 是       |
| pageSize   | Integer    | 否       |
| pageNumber | Integer    | 否       |



# 出参

| 字段    | 类型       | 值                                                           |
| ------- | ---------- | ------------------------------------------------------------ |
| status  | Integer    | 1 成功<br />其它值失败                                       |
| message | string     | status的描述                                                 |
| data    | JsonObject | {<br />bean:CarReceive<br />pageParams:`Map<String,Object>`<br />page:`Page<CarReceive>`<br />} |


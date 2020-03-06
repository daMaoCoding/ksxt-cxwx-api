# 入参

* url：```https://2858y3h397.qicp.vip/cxwx/supplierEnt/list```
* type:GET
* params:

| 字段       | 类型        | 是否必填 |
| ---------- | ----------- | -------- |
| token      | string      | 是       |
| bean       | SupplierEnt | 是       |
| pageSize   | Integer     | 是       |
| pageNumber | Integer     | 是       |



# 出参

| 字段    | 类型       | 值                                                           |
| ------- | ---------- | ------------------------------------------------------------ |
| status  | Integer    | 1 成功<br />其他值失败                                       |
| message | string     | status的描述信息                                             |
| data    | JsonObject | {<br />bean:SupplierEnt<br />pageParams:SupplierEnt类型字段名为key，值为value的map<br />page：Page`<SupplierEnt>`<br />} |


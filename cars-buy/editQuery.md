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

# 示例

* 请求

> `https://2858y3h397.qicp.vip/cxwx/carReceive/edit?token=123456&id=278f04e05f7811ea8903f3976f2eeb7e`

* 响应

> {
>   "state" : 1,
>   "message" : "OK",
>   "data" : {
>     "dropList" : [ ],
>     "bean" : {
>       "excludeOperateId" : null,
>       "dealUserId" : null,
>       "states" : null,
>       "order" : null,
>       "pageSize" : null,
>       "currentPage" : null,
>       "id" : "278f04e05f7811ea8903f3976f2eeb7e",
>       "plateNumber" : "桂A1234151",
>       "tare" : null,
>       "maxLoad" : null,
>       "carType" : null,
>       "vin" : null,
>       "engineNo" : null,
>       "carOwner" : "test",
>       "driver" : "test",
>       "idNumber" : null,
>       "mobile" : "13800138000",
>       "address" : null,
>       "status" : null,
>       "entId" : null,
>       "dropId" : null,
>       "remark" : null,
>       "entName" : null,
>       "createTime" : 1583478025263,
>       "creater" : "3f4e653016b711ea5a6df2513cec98d3",
>       "modifyTime" : null,
>       "modifier" : null,
>       "sort" : null,
>       "receiveEntId" : null,
>       "ids" : null
>     }
>   }
> }
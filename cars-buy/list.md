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

# 示例

* 请求

> `https://2858y3h397.qicp.vip/cxwx/carReceive/listByPage?token=123456&pageNumber=2&pageSize=100&plateNumber=桂测试123456`

* 响应

> {
>   "state" : 1,
>   "message" : "OK",
>   "data" : {
>     "pageParams" : {
>       "pageNumber" : 2,
>       "pageSize" : 100,
>       "plateNumber" : "桂测试123456",
>       "token" : "123456"
>     },
>     "bean" : {
>       "excludeOperateId" : null,
>       "dealUserId" : null,
>       "states" : null,
>       "order" : null,
>       "pageSize" : 100,
>       "currentPage" : null,
>       "id" : null,
>       "plateNumber" : "桂测试123456",
>       "tare" : null,
>       "maxLoad" : null,
>       "carType" : null,
>       "vin" : null,
>       "engineNo" : null,
>       "carOwner" : null,
>       "driver" : null,
>       "idNumber" : null,
>       "mobile" : null,
>       "address" : null,
>       "status" : null,
>       "entId" : null,
>       "dropId" : null,
>       "remark" : null,
>       "entName" : null,
>       "createTime" : null,
>       "creater" : null,
>       "modifyTime" : null,
>       "modifier" : null,
>       "sort" : null,
>       "receiveEntId" : null,
>       "token" : "123456",
>       "pageNumber" : 2,
>       "ids" : null
>     },
>     "page" : {
>       "pageNumber" : 2,
>       "pageSize" : 100,
>       "totalCount" : 0,
>       "pageCount" : 0,
>       "content" : [ ],
>       "param" : { }
>     }
>   }
> }
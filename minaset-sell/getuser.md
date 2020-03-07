# 入参

* url:```https://2858y3h397.qicp.vip/cxwx/mineral/getuser```
* type:GET
* params:

| 字段  | 类型       | 是否必填 |
| ----- | ---------- | -------- |
| token | string     | 是       |
| bean  | MineralDto | 否       |



# 出参

| 字段    | 类型       | 值                                        |
| ------- | ---------- | ----------------------------------------- |
| status  | string     | 1 成功<br />其他表示失败                  |
| message | string     | 对status的描述                            |
| data    | JsonObject | {List`<Mineral>`的列表字符串<br />code:0} |

# 示例

* 请求

> `https://2858y3h397.qicp.vip/cxwx/mineral/getuser?token=123456`

* 响应

> {
>   "state" : 1,
>   "message" : "OK",
>   "data" : {
>     "code" : "0",
>     "list" : [ {
>       "excludeOperateId" : null,
>       "dealUserId" : null,
>       "states" : null,
>       "order" : null,
>       "pageSize" : null,
>       "currentPage" : null,
>       "id" : "0fb5a1c07a1e11e974b14704957c2a21",
>       "mineralNo" : "",
>       "name" : "1-2石",
>       "remark" : "兴明",
>       "status" : 1,
>       "createTime" : 1558260514000,
>       "creater" : "18BFB6258FC64649865537A853A6C286",
>       "modifyTime" : null,
>       "modifier" : null,
>       "sort" : null,
>       "ppId" : "c51c3470618711e9f06d570db58aee52",
>       "isApp" : 0,
>       "isReceive" : 0,
>       "isReceiveZxsb" : 0,
>       "isReceiveGddz" : 0,
>       "price" : null,
>       "zhengFang" : null,
>       "startTime" : null,
>       "endTime" : null,
>       "yhPrice" : null,
>       "ids" : null
>     }]
>   }
> }
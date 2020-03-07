# 入参

* url:```https://2858y3h397.qicp.vip/cxwx/mineralEntSet/list```
* type:GET
* params:

| 字段     | 类型   | 是否必填 |
| -------- | ------ | -------- |
| token    | string | 是       |
| chargeId | string | 是       |



# 出参

| 字段    | 类型       | 值                     |
| ------- | ---------- | ---------------------- |
| status  | Integer    | 1 成功<br />其他值失败 |
| message | string     | status的描述           |
| data    | JsonObject | {<br />}               |

# 示例

* 请求

>`https://2858y3h397.qicp.vip/cxwx/mineralEntSet/list?token=123456&chargeId=0be42680593d11ea12bd32d1c58070fe`
>
>

* 响应

>{
>  "state" : 1,
>  "message" : "OK",
>  "data" : {
>    "list" : [ ]
>  }
>}
>
>
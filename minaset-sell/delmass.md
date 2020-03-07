# 入参

* url:```https://2858y3h397.qicp.vip/cxwx/MineralEnt/delmass```
* type:GET
* params:

| 字段  | 类型   | 是否必填 |
| ----- | ------ | -------- |
| token | string | 是       |
| id    | String | 是       |



# 出参

| 字段    | 类型       | 值                       |
| ------- | ---------- | ------------------------ |
| status  | string     | 1 成功<br />其他表示失败 |
| message | string     | 对status的描述           |
| data    | JsonObject | {<br />code:0<br />}     |

# 示例

* 请求

> `https://2858y3h397.qicp.vip/cxwx/MineralEnt/delmass?token=123456&id=4101e54059d911ea12bd32d1c58070fe`

* 响应

> {
>   "state" : 1,
>   "message" : "OK",
>   "data" : {
>     "code" : "0"
>   }
> }
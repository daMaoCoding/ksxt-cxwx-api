# 入参

* url:```https://2858y3h397.qicp.vip/cxwx/MineralEnt/addmass```
* type:POST
* params:

| 字段   | 类型       | 是否必填 |
| ------ | ---------- | -------- |
| token  | string     | 是       |
| id     | String     | 是       |
| danjia | BigDecimal | 是       |
| zfxs   | BigDecimal | 是       |



# 出参

| 字段    | 类型       | 值                       |
| ------- | ---------- | ------------------------ |
| status  | string     | 1 成功<br />其他表示失败 |
| message | string     | 对status的描述           |
| data    | JsonObject | {<br />code:0<br />}     |

# 示例

* 请求

> {
> "token":123456,
> "id":"177482f07a1e11e974b14704957c2a21",
> "danjia": "1",
> "zfxs": "1",
> "inventory": "2",
> "place": "test"
> }

* 响应

> {
>   "state" : 1,
>   "message" : "OK",
>   "data" : {
>     "code" : "0"
>   }
> }
# 入参

* url:```https://2858y3h397.qicp.vip/cxwx/MineralEnt/updateMassger```
* type:POST
* params:

| 字段  | 类型       | 是否必填 |
| ----- | ---------- | -------- |
| token | string     | 是       |
| bean  | MineralEnt | 否       |



# 出参

| 字段    | 类型       | 值                                        |
| ------- | ---------- | ----------------------------------------- |
| status  | string     | 1 成功<br />其他表示失败                  |
| message | string     | 对status的描述                            |
| data    | JsonObject | {<br />code:0 ,表示成功，1表示失败<br />} |

# 示例

* 请求

> {
> "token":123456,
> "id":"0344a6309ee911e92e1ee9a8481aca5b",
> "danjia": "2",
> "zfxs": "2",
> "inventory": "2",
> "place": "test"
> }

* 响应

> {
>   "state" : 1,
>   "message" : "OK",
>   "data" : {
>     "code" : 0
>   }
> }
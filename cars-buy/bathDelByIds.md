# 入参

* url：```https://2858y3h397.qicp.vip/cxwx/carReceive/bathDelByIds```
* type:GET
* params:

| 字段  | 类型           | 是否必填 |
| ----- | -------------- | -------- |
| token | string         | 是       |
| ids   | `List<String>` | 是       |



# 出参

| 字段    | 类型    | 值                     |
| ------- | ------- | ---------------------- |
| status  | Integer | 1 成功<br />其他值失败 |
| message | string  | status描述             |

# 示例

* 请求

>`https://2858y3h397.qicp.vip/cxwx/carReceive/bathDelByIds?token=123456&ids=ceedeae05f8111ea3ee25cfefa6b96b0`

* 响应

>{
>  "state" : 1,
>  "message" : "OK",
>  "data" : null
>}
>
>
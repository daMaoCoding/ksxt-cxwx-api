# 入参

* url：```https://2858y3h397.qicp.vip/cxwx/carReceive/save```
* type:POST
* params:

| 字段  | 类型       | 是否必填 |
| ----- | ---------- | -------- |
| token | string     | 是       |
| bean  | CarReceive | 是       |



# 出参

| 字段    | 类型    | 值                     |
| ------- | ------- | ---------------------- |
| status  | Integer | 1 成功<br />其它值失败 |
| message | string  | status的描述           |

# 示例

* 请求

> {
> 	"token":"123456",
> 	"plateNumber":"123456",
> 	"carOwner":"654321",
> 	"driver":"test",
> 	"mobile":"13800138000"
> }

* 响应

>
>
>{
>  "state" : 1,
>  "message" : "OK",
>  "data" : null
>}

# 示例

* 请求

>{
>	"token":"123456",
>	"id":"278f04e05f7811ea8903f3976f2eeb7e",
>	"plateNumber":"桂A1234151",
>	"carOwner":"test2",
>	"driver":"test2",
>	"mobile":"13800138000"
>}

* 响应

>{
>	"token":"123456",
>	"id":"278f04e05f7811ea8903f3976f2eeb7e",
>	"plateNumber":"桂A1234151",
>	"carOwner":"test2",
>	"driver":"test2",
>	"mobile":"13800138000"
>}
>
>
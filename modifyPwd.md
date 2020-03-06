# 入参：

* url：```https://2858y3h397.qicp.vip/cxwx/modifyPwd```

* type:POST

* params:

| 字段   | 类型   | 是否必填 |
| ------ | ------ | -------- |
| token  | string | 是       |
| oldPwd | string | 是       |
| newPwd | string | 是       |

# 出参：

| 字段    | 类型   | 值                    |
| ------- | ------ | --------------------- |
| status  | String | 0 表示成功  1表示失败 |
| message | String | status对应的描述信息  |

# 示例

* 输入

> {
> 	"token":"123456",
> 	"oldPwd":"123456",
> 	"newPwd":"654321"
> }

* 输出

> {
>   "state" : 1,
>   "message" : "旧密码不对",
>   "data" : null
> }


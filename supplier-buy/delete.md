# 入参

* url:```https://2858y3h397.qicp.vip/cxwx/supplierEnt/supplierEntdelect```
* type:GET
* params:

| 字段  | 类型         | 是否必填 |
| ----- | ------------ | -------- |
| token | string       | 是       |
| ids   | List的字符串 | 是       |



# 出参

| 字段    | 类型    | 值                     |
| ------- | ------- | ---------------------- |
| status  | Integer | 1 成功<br />其他值失败 |
| message | string  | status的描述信息       |

# 示例

* 请求

>`https://2858y3h397.qicp.vip/cxwx/supplierEnt/supplierEntdelect?token=123456&ids=c5aa0b005fbb11eae8b5d0b2bb72b9f2`
>
>

* 响应

>{
>  "state" : 1,
>  "message" : "删除成功！",
>  "data" : null
>}
>
>